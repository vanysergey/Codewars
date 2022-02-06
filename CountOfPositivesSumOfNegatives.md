# Codewars

## Count of positives  sum of negatives

Given an array of integers.

Return an array, where the first element is the count of positives numbers and the second element is sum of negative numbers. 0 is neither positive nor negative.

If the input array is empty or null, return an empty array.

Example
For input [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, -11, -12, -13, -14, -15], you should return [10, -65].

# Solution:
```
function countPositivesSumNegatives(input) {
  if(!input || !input.length) return [];
  let a=0, b=0;
  input.forEach(el => {
    if(el > 0) {
      a++;} 
    else {
      b+=el}
  });
  return [a, b];
}
```
