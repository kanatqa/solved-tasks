# solved-tasks
*task 1
```javascript
const a = 122;
```
*task 2: Sum of differences in array
```javascript
function sumOfDifferences(a) {
let result = 0;
let b = [];
let c = 0;
let sum = a.sort(function(a, b){return a - b});
for(let i = sum.length -1; i >= 0; i--){
  result  = (sum[i] - sum[i - 1]);
  if(!(isNaN(result))){
    c = c + result;
  }
}
    return c;
  
}
```

#task 3: Beginner - Lost Without a Map

```javascript
function maps(x){
let result  = [];
x.map(function(num){
  result.push(num*2);
})
return result;
}
```

*task 4: Who is going to pay for the wall?
```javascript
function whoIsPaying(name){
  //your code here
  let fullName = [];
  if(name.length > 2){
     fullName.push(name);
     fullName.push(name.substring(0,2));
  }else {
    fullName.push(name);
  }
  return fullName
}
```

