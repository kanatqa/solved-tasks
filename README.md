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
*task 5: Well of Ideas - Easy Version
```javascript
function well(x){
let count = 0;
  for(let i = 0; i < x.length; i++){
    if(x[i] === 'good'){
      count++;
    }
  }
  if(count === 0){
    return 'Fail!';
  }else if(count == 1 || count == 2){
    return 'Publish!';
  }else if(count > 2){
    return 'I smell a series!'
  }
}
```
*task 6: Remove String Spaces
```javascript
function noSpace(x){
  return x.replace(/\s/g, '');
}
```
*task 7: Breaking chocolate problem
```javascript
function noSpace(x){
  return x.replace(/\s/g, '');
}
```
*task 8: Calculate BMI
```javascript
function bmi(weight, height) {
  let result = '';
  let bmi = weight/Math.pow(height,2);
  if(bmi <= 18.5){
    return 'Underweight'
  }else if(bmi > 18.5 && bmi <= 25.0){
    return 'Normal'
  }else if(bmi > 25 && bmi <= 30){
    return 'Overweight'
  }else if(bmi > 30){
    return 'Obese'
  }

  return "";
}
```
*task 9: [JS 8kyu] 5 without numbers !!
```javascript
function unusualFive() {
  return 'wwwww'.length;
}
```
*task 10: [JS 8kyu] - Playing with cubes I
```javascript
        public class Cube{
            private int side;
            int getSide(){
              return side;
            }
            void setSide(int num){
              side = num;
            }
          }
```
         