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
*task 9: JS 8kyu 5 without numbers !!
```javascript
function unusualFive() {
  return 'wwwww'.length;
}
```
*task 10: Java 8kyu - Playing with cubes I
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
public class EncapsulationDemo{
  public int number;
  public String stringValue;
  public Object anObject;
  
  public int getNumber(){
    return number;
  }
  public void setNumber(int number){
    this.number = number;
  }
  
  public String getStringValue(){
    return stringValue;
  }        
  public void setStringValue(String stringValue){
    this.stringValue = stringValue;
  }
  
  public Object obObject(){
    return anObject;
  }
  public void setObObject(Object anObject){
    this.anObject = anObject;
  }
}

```

*test11 java 7kyu Lombok Encapsulation
```javascript


public class EncapsulationDemo{
  private int number;
  private String stringValue;
  private Object anObject;
  
  
  EncapsulationDemo(){
  
  }
  EncapsulationDemo(int number, String stringValue, Object anObject){
    this.number = number;
    this.stringValue = stringValue;
    this.anObject = anObject;
  
  }
  
  public int getNumber(){
    return number;
  }
  public void setNumber(int number){
    this.number = number;
  }
  
  public String getStringValue(){
    return stringValue;
  }        
  public void setStringValue(String stringValue){
    this.stringValue = stringValue;
  }
  
  public Object getAnObject(){
    return anObject;
  }
  public void setAnObject(Object anObject){
    this.anObject = anObject;
  }
}
```
*task11: 8 kyu Training JS #1: create your first JS function and print "Helloworld!"
```javascript

helloWorld = function() {
  var str = "Hello World!";
  console.log( str );
}
```
*task12: Sum of angles
```javascript
function angle(n) {
  return (n - 2) * 180;
}
```
*task 13: Third Angle of a Triangle
```javascript
function otherAngle(a, b) {

  return 180 - (a + b);
}
```