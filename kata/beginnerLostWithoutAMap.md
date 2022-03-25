# Codewars

## Beginner - Lost Without a Map

Given an array of integers, return a new array with each value doubled.

For example:

[1, 2, 3] --> [2, 4, 6]

# Solution:
```
function maps(x){
let array = [];
for (let i = 0; i < x.length; i++){
array.push(x[i] * 2);
}
return array;
}
```
or
```
function maps(x){
  return x.map(x => x*2);
}
```
