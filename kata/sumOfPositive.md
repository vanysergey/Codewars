# Codewars

## Sum of positive

You get an array of numbers, return the sum of all of the positives ones.

```Example [1,-4,7,12] => 1 + 7 + 12 = 20```

Note: if there is nothing to sum, the sum is default to 0.

# Solution:
```
function positiveSum(arr) {
  let a=0; 
  arr.forEach(el => {
    if(el > 0) {
      a+=el;} 
    else if (el <0) {
      a+= 0;
  } else {
      return 0;
    }
    });
  return (a);
}
```
