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

*task 3: Beginner - Lost Without a Map

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
*task 14: I love you, a little , a lot, passionately ... not at all
```javascript
/*
===

best solution:
howMuchILoveYou = n => ['I love you', 'a little', 'a lot', 'passionately', 'madly', 'not at all'][(n - 1) % 6]

===
*/
function howMuchILoveYou(nbPetals) {
    // your code
    let petals = ['I love you',
        'a little',
        'a lot',
        'passionately',
        'madly',
        'not at all'];
  
  if(nbPetals< 7){
    for(let i = 0; i <= petals.length; i++){
        if(nbPetals === i){
            return petals[i - 1];
        }
    }
  }else if (nbPetals = nbPetals %6){
        for(let i = 0; i <= petals.length; i++){
        if(nbPetals === i){
            return petals[i - 1];
        }
    }
  }else if(nbPetals == 0) return 'not at all';
  
  }


```
*task 15: For Twins: 2. Math operations
```javascript
function iceBrickVolume(radius, bottleLength, rimLength) {
  // Your code should be here ;)
  
  let heigth = bottleLength - rimLength;
  
  return radius * radius  * heigth * 2;
}
```
*task16: Convert boolean values to strings 'Yes' or 'No'.
```javascript
function boolToWord( bool ){
  //...
  return (bool) ? 'Yes' : 'No';
}

```
*task 17: Super Duper Easy
```javascript
function problem(x){
  //your code here
  return (typeof x === 'number') ? x * 50 + 6 : 'Error';
}
```
*task 18: Chuck Norris VII - True or False? (Beginner)
```javascript
function ifChuckSaysSo(){
return undefined === null;

}
```
*task19: Convert a Number to a String!
```javascript
function numberToString(num) {
  // Return a string of the number here!
  return num.toString();
}
```

*task20: Convert a String to a Number!
```javascript
var stringToNumber = function(str){
  // put your code here
  if(typeof str === 'string'){
  return +str;
  }
  else{
  return null;
  }
}
```

*task21: Number toString
```javascript
var a = 123;
a = a.toString();
```
*task22: Convert a Boolean to a String
```javascript
function booleanToString(b){
  //your code here
  if(b === true){
  return 'true';
  }else{
  return 'false';
  }
}
```
*task23: Century From Year
```javascript
function oddCount(n){
  // your code here
  return Math.ceil(n / 2 - 1);
}
```
*task24: Count Odd Numbers below n
```javascript
function oddCount(n){
  // your code here
  n = Math.round(n / 2 + 0.5) -1;
  return n;
}
```
*task25: Keep Hydrated!
```javascript
function litres(time) {
  if(time < 1.5){
    return 0;
  }else{
    return Math.floor(time * 0.5);
  }
}
```
*task26: Return the closest number multiple of 10
```javascript
const closestMultiple10 = num => {
  num = Math.round(num / 10);
  num = num * 10;
  return num;
};
```
*task27: How many times should I go?
```javascript
function howManyTimes(annualPrice, individualPrice) {
  return Math.ceil(annualPrice / individualPrice);
}
```
*task28: Formatting decimal places #0
```javascript
function twoDecimalPlaces(n) {
  // Your code here
  let x =  +n.toFixed(2);
  return x;
}
```
*task29: Area of a Square
```javascript
function squareArea(A){
let x = (A * (2 / Math.PI)) ** 2;
  return +x.toFixed(2);
}
```
*task30: Discover The Original Price
```javascript
function discoverOriginalPrice(discountedPrice, salePercentage){
  // ...
  let sum = 100 - salePercentage;
  let sum1 = (discountedPrice / sum) * salePercentage;
  let sum2 = (sum1 + discountedPrice).toFixed(2);
      return +sum2;

}
<<<<<<< HEAD
<<<<<<< HEAD
```
*task31 Calculate Two People's Individual Ages

```javascript
function getAges(sum,difference){
 let result = [];
 if(sum < 0|| difference < 0  || sum <= difference && sum != difference ){
  return null;
 } else if(sum  == difference){ 
   result.push(sum);
   result.push(0);
 
 }else{
 console.log(sum, difference);
  result.push((Math.abs((difference % sum)  -  sum)/ 2 + difference));
  result.push((Math.abs((difference % sum)  -  sum)/ 2 ));
 }
 return result;
};

```
*task32: Is n divisible by x and y?
```javascript
function isDivisible(n, x, y) {
 if(n % x == 0 && n % y == 0){
   return true;
 }
 else{
   return false;
 }
}
```
*task33: How satisfied are you with this kata?
```javascript
function isTriangle(a,b,c)
{
console.log(a, b, c);
  if (a > 0 && b > 0 && c > 0 && ((c - b < a ) && (a  < c + b) && (a + b > c) && (b < c + a))){
    return true;
  }
  else {
   return false;
  }
}
```
*task34: Rock Paper Scissors!
```javascript
const rps = (p1, p2) => {
console.log(p1, p2);

if((p1 === 'rock' && p2 === 'scissors') ||  (p1 === 'scissors' &&  p2 === 'paper') ||  (p1 === 'paper' &&  p2 == 'rock')){
  return 'Player 1 won!';
}else if(p1 == p2){
  return 'Draw!';
}else { return 'Player 2 won!'}
};
```
*task35: L1: Set Alarm

```javascript
function setAlarm(employed, vacation){
  if(employed === true && vacation === false){
    return true;
  }else { return false;}
}
```
*task36: Can we divide it?
```javascript
function isDivideBy(number, a, b) {
  // good luck
  return ((number % a == 0) && (number % b == 0)) ? true : false;
}
```
*task37: Be Concise I - The Ternary Operator
```javascript
let describeAge = (b) =>{a="You're a(n) ";return b<13 ? a+"kid" : b>12 && b<18 ? a+"teenager" : b>17 && b<65 ? a+"adult": a+"elderly";}

```
*task38: 101 Dalmatians - squash the bugs, not the dogs!
```javascript
function howManyDalmatians(number){
  
  var dogs = ["Hardly any", "More than a handful!", "Woah that's a lot of dogs!", "101 DALMATIANS!!!"];
  
  var respond = (number <= 10) ? dogs[0] :(number <= 50) ? dogs[1] : (number == 101) ? dogs[3] : dogs[2];
  
return respond
}
```
*task39: Training JS #7: if..else and ternary operator
```javascript
function saleHotdogs(n){
  return (n < 5) ? n * 100 : (n >= 5 && n < 10) ? n * 95 : (n >= 10) ? n * 90 : 0;
}
```

*task40: Basic Mathematical Operations
```javascript

function basicOp(operation, value1, value2)
{
  // Code
  let sum = 0;
switch(operation){
  case '+':
  sum = value1 + value2;
  break;
  case '-':
  sum = value1 - value2;
  break;
  case '*':
  sum = value1 * value2;
  break;
  case '/':
  sum = value1 / value2;
  break;
}
return sum;
}

```
*task41: simple calculator
```javascript
function calculator(a,b,sign){

  // Code
  let sum = 0;
  
switch(sign){
  case '+':
  sum = a + b;
  break;
  case '-':
  sum = a - b;
  break;
  case '*':
  sum = a * b;
  break;
  case '/':
  sum = a / b;
  break;
  
}
if(Number(sum)){
    return sum;
  }else{ return "unknown value";}
  

}

```
*task42 
```javascript
Power of two


function isPowerOfTwo(n){
  //.. should return true or false ..
let i = 0;
let sum = 1;

while(sum < n){

  sum =  2 * sum;
      i++;

}
return (Math.pow(2, i) == n) ? true : false;
}

--------------------
Difference Of Squares


function differenceOfSquares(n){
  // ...
  let sum = 0;
  let i = 0;
  let b = 0;
  while(i <= n){
    sum += Math.pow(i, 2);
    b += i;
    i++;
        console.log(sum);

  }
  return (Math.pow(b, 2)- sum);
}

-------------------
No zeros for heros


function noBoringZeros(n) {
  // your code
let str = '' + n;
let i = str.length -1 ;

while(i  > -1 && str[i] === '0'){
  str = str.slice(0, -1);
  i--;
  
}
      return +str;
}

-----------
Factorial

function factorial(n){
let sum = 1;

while(n > 0){
sum = n * sum;
      n--;


}
return sum;
}


----------------
Sum of Multiples

function sumMul(n,m){
//your idea here
let result = 0;
  if(m <= 0){
    return "INVALID";
  }else{
      console.log(n + ' ' + m);
    for(let i = n; i < m; i = i + n){
       result = result + i;
      
    }
    return result;
  }
  
}
--------------------
Filter the number

var FilterString = function(value) {
  //Complete this function :)
  let a = [...value];
let result = [];
console.log(a);
for (let i = 0; i < value.length; i++) { 
  if (!isNaN(a[i])) {
    
  result.push(a[i]); 
 }
}
return (+result.join(''));
}
--------------------
isReallyNaN

const isReallyNaN = (val) => {
  // return isNaN(val);  // wasn't working as planned :-(
  console.log(val);
  return (Number.isNaN(val)) ? true : false;
};
--------------------
Is integer safe to use?

function SafeInteger(n) {
return (Number.isSafeInteger(n));
}
--------------------
Return Negative


function makeNegative(num) {
  // Code?
  return (num >= 0) ? -num : num;
}
--------------------
BASIC: Making Six Toast.


function sixToast(num) {
  // you code here
  let a = 6 - num;
  return Math.abs(a);
}


-------------------
Closest elevator


function elevator(left, right, call){
  // code on! :)
  return Math.abs((left - call)) < Math.abs((right - call)) ? 'left' : 'right';
}

-------------------
Square Every Digit


function squareDigits(num){
  //may the code be with you
  num = num + '';
 let a = [...num];
console.log(num);
let result = [];
  for(let i = 0; i < a.length; i++){
    result.push(Math.pow(a[i], 2));
  }
  return +(result.join(''));
  
}
-------------------
You're a square!


var isSquare = function(n){
console.log(n);
  
let result = Math.sqrt(n);
if(n<0){
  return false; // fix me
}else if(!Number.isInteger(result)){
  return false;
}else return true;
}
-------------------
Find the next perfect square!

function findNextSquare(sq) {
  // Return the next square if sq if a perfect square, -1 otherwise
  let res = 0;
if(Number.isInteger(Math.sqrt(sq))){
  res = Math.sqrt(sq);
  return Math.pow(res +1, 2)
  
}else   return -1;

}
-------------------
Power of two

function isPowerOfTwo(n){
  //.. should return true or false ..
  return Number.isInteger(Math.log2(n));
}
-------------------
Beginner Series #4 Cockroach

function cockroachSpeed(s) {
  //Good Luck!
  return Math.floor(s * 27.777778);
}
-------------------
Price of Mangoes

function mango(quantity, price){
  return (quantity - Math.floor(quantity / 3))*price;
}
-------------------
Holiday VIII - Duty Free

function dutyFree(normPrice, discount, hol){
return Math.floor((hol / normPrice) / (discount / 100))
}

-------------------
Tortoise racing

function race(v1, v2, g) {
    // your code
if(v1 >= v2) return null;
console.log(v1 + ' ' + v2 + ' ' + g);
let c = (g / (v2 - v1))
let resultTime = [];
var hour = Math.floor(Math.abs(c));
 var mint = Math.floor((Math.abs(c) * 60) % 60);
 var sec = Math.floor((Math.abs(c) * 3600) % 60);
resultTime.push(hour, mint, sec);
return (resultTime);
}
-------------------
Formatting decimal places #1

function twoDecimalPlaces(a) {
  // Your code here
  return Math.trunc((a - Math.trunc(a)) * 100) / 100 + (Math.trunc(a));
}
-------------------
Lario and Muigi Pipe Problem

function pipeFix(a){
let b = [];
for(let i = Math.min(...a); i <= Math.max(...a); i++){
  b.push(i);
  
}
return (b);

}
-------------------
Expressions Matter

function expressionMatter(a, b, c) {
  return (Math.max((a + b  + c), (a * (b + c)), (a * b * c), (a + b * c), ((a + b) * c)));// highest achievable result
  
}
-------------------
Convert to Binary

function toBinary(n){
  return +n.toString(2);
}
-------------------
Binary Addition

function addBinary(a,b) {
return (a+b).toString(2);
}
-------------------
Calculate Price Excluding VAT

//return price without vat
function excludingVatPrice(a){
  // your code
  return (a === null) ? -1 : +((a - (a / (1 + 0.15) * 0.15)).toFixed(2));
}
-------------------
Parse nice int from char problem

function getAge(inputString){
// return correct age (int). Happy coding :) 
return Number.parseInt(inputString);
}

-------------------
Hex to Decimal

hexToDec = hexString => Number.parseInt(hexString, 16);

-------------------
Bin to Decimal

binToDec = bin => parseInt(bin, 2);
-------------------
Parse float

parseF = (s) => (!parseFloat(s) && parseFloat(s) !== 0) ? null : parseFloat(s);
-------------------
Sum Arrays

// Sum Numbers
function sum (numbers) {
    "use strict";
    let sum = 0;
    for(let i = 0; i < numbers.length; i++){
      sum += numbers[i];
    }
    
    return sum;
};
-------------------
Filling an array (part 1)

function arr( N){
let arr = [];
for(let i = 0; i < N; i++){ 
arr.push(i)
}
return arr;
}



}


```
*task 45 
```javascript
const arrCheck = value => (toString.call(value[1]).slice(8, -1).toLowerCase() === "array") ? true : false ;

```
*task 46
```javascript
function type(a) {
  let b = toString.call(a).toLowerCase(a).split(' ').pop()

return (b.split(']').slice(0, -1).join('/'));
```