Hello
________________________


## 6/24

[https://www.codewars.com/kata/thinkful-logic-drills-traffic-light/train/javascript]

```javascript
function updateLight(current) {
  if (current === "green") {
    return "yellow";
  }
  if (current === "yellow") {
    return "red";
  }
  if (current === "red") {
    return "green";
  }
}
```

[https://www.codewars.com/kata/the-feast-of-many-beasts/train/javascript]

```javascript
function feast(beast, dish) {
if(beast[0] === dish[0] && beast.charAt(beast.length-1) === dish.charAt(dish.length-1)){
  return true;
  }
  else return false;
}
```

[https://www.codewars.com/kata/simple-multiplication/train/javascript]

```javascript
function simpleMultiplication(number) {
  if(number % 2 === 0){
  return number * 8;
  }
  else return number * 9;
}
```

## 6/25

[https://www.codewars.com/kata/switch-it-up/train/javascript]

```javascript
function switchItUp(number){
 switch(number){
  case 0:
  return 'Zero';
  break;
  case 1: 
  return 'One';
  break;
  case 2: 
  return 'Two';
  break;
  case 3: 
  return 'Three';
  break;
  case 4: 
  return 'Four';
  break;
  case 5: 
  return 'Five';
  break;
  case 6: 
  return 'Six';
  break;
  case 7: 
  return 'Seven';
  break;
  case 8: 
  return 'Eight';
  break;
  case 9: 
  return 'Nine';
  break;
  case 10:
  return 'Ten';
  break;
}
}
```

[https://www.codewars.com/kata/students-final-grade/train/javascript]

```javascript
function finalGrade (exam, projects) {
  if ((exam > 90 && exam <= 100) || projects > 10){
    return 100;
    }
  if (exam > 75 && projects >= 5){
    return 90;
    }
  if (exam > 50 && projects >= 2){
    return 75;
    }
  else return 0;
}
```

[https://www.codewars.com/kata/sleigh-authentication/train/javascript]

```javascript
function Sleigh() {}

Sleigh.prototype.authenticate = function(name, password) {
if (name === 'Santa Claus' && password === 'Ho Ho Ho!') {
 return true;
 }
 else return false
};
```

[https://www.codewars.com/kata/5a2e9ae2b6cfd7692a0000ba]

```javascript
function typeOfSum(a, b) {
let sum = a + b;
  if (typeof sum === 'number'){
    return 'number';
    }
    else return 'string';
}
```

[https://www.codewars.com/kata/convert-a-string-to-an-array/train/javascript]

```javascript
function stringToArray(string){
const arr = string.split(" ");
return arr;
}
```

[https://www.codewars.com/kata/array-plus-array/train/javascript]

```javascript
function arrayPlusArray(arr1, arr2) {
let sum = 0;
for(let i = 0; i < arr1.length; i++){
  sum += arr1[i]
}
for(let j = 0; j < arr2.length; j++){
 sum += arr2[j];
}
  return sum; 
}
```

[https://www.codewars.com/kata/credit-card-issuer-checking/train/javascript]

```javascript
function getIssuer(number) {
  if((number.toString().substring(0, 2) === '34' || 
     number.toString().substring(0, 2) === '37') && number.toString().length === 15) 
    {
    return 'AMEX';
    }
  else if (number.toString().substring(0, 4) === '6011' && number.toString().length === 16)
    {
    return 'Discover';
    }
  else if ((number.toString().substring(0,2) === '51' ||
            number.toString().substring(0,2) === '52' ||
            number.toString().substring(0,2) === '53' ||
            number.toString().substring(0,2) === '54' ||
            number.toString().substring(0,2) === '55') && number.toString().length === 16) 
    {
    return 'Mastercard';
    }
  else if (number.toString().substring(0,1) === '4' && 
          (number.toString().length === 13 || number.toString().length === 16))
    {
    return 'VISA';
    }
    else return 'Unknown';
}

```

##6/26

[https://www.codewars.com/kata/remove-string-spaces/train/javascript]

```javascript
function noSpace(x){
  let str = x.replace(/\s/g, '');
  return str;
}
```

[https://www.codewars.com/kata/do-i-get-a-bonus/train/javascript]

```javascript
function bonusTime(salary, bonus) {
  if (bonus === true){
  return '\u00A3'+(salary * 10);
} else return '\u00A3'+salary;
}
```

[https://www.codewars.com/kata/returning-strings/train/javascript]

```javascript
function greet(name){
  return `Hello, ${name} how are you doing today?`
}
```

[https://www.codewars.com/kata/string-ends-with/train/javascript]

```javascript
function solution(str, ending){
  let strNew = str.slice(-(ending.length));
  if (strNew === ending){
  return true;
  }
  else return false;
}
```
## 6/27
added new solution


add solution to master 

added one more solution to master 


_new-branch_**
new-branch solution

new branch solution-V2

new branch solution_V2.1

## 6/29 -V1

[https://www.codewars.com/kata/reversed-sequence/train/javascript]

```javascript
const reverseSeq = n => {
const arr = [];
for(let i = n; i >=1; i--){
  arr.push(i);
}
  return arr;
}
```

[https://www.codewars.com/kata/fixme-replace-all-dots/train/javascript]
```javascript
var replaceDots = function(str) {
let strNew = str.replace(/\./g, '-');
  return strNew;
}
```

[https://www.codewars.com/kata/string-cleaning/train/javascript]
```javascript
function stringClean(s){
let sNew = s.replace(/\d/g, '');
return sNew;
}
```
[https://www.codewars.com/kata/third-angle-of-a-triangle/train/javascript]
```javascript
function otherAngle(a, b) {
let totalDegree = 180;
let sum = a + b;
  return totalDegree - sum;
}
```

## 6/29 - v2

[https://www.codewars.com/kata/abbreviate-a-two-word-name/train/javascript]
```javascript
function abbrevName(name){
let nameIn;
  for(let i = 1; i < name.length; i++){
    if(name[i] === ' '){
    nameIn = name[0].toUpperCase() + '.' +name[i+1].toUpperCase();
    }
  }
  return nameIn;
}
```

[https://www.codewars.com/kata/you-only-need-one-beginner/train/javascript]

```javascript
function check(a,x){
return a.includes(x);
}
```

[https://www.codewars.com/kata/man-in-the-west/train/javascript]

```javascript
function checkTheBucket(bucket){
  return bucket.includes('gold');
}
```

[https://www.codewars.com/kata/count-odd-numbers-below-n/train/javascript]

```javascript
function oddCount(n){
    return (n-1)/2;
}

function oddCount(n){
    return Math.floor(n/2);
}
```




##6/30 

CW solutions in a new-branch:

[https://www.codewars.com/kata/reverse-list-order/train/javascript]

```javascript
function reverseList(list) {
const arr = [];
  for(let i = list.length-1; i >= 0 ; i--){
  arr.push(list[i]);
  }
  return arr;
}
```

[https://www.codewars.com/kata/jennys-secret-message/train/javascript]

```javascript
unction greet(name){
  if(name === "Johnny"){
    return "Hello, my love!";
    }
  else return "Hello, " + name + "!";
}
```

[https://www.codewars.com/kata/super-duper-easy/train/javascript]

```javascript 
function problem(x){
if (typeof x === 'string'){
  return 'Error';
  }
else return (x * 50) + 6;
}
```

[https://www.codewars.com/kata/unfinished-loop-bug-fixing-number-1/train/javascript]

```javascript
function createArray(number){
  var newArray = [];
  for(let i = 1;  i <= number; i++){
    newArray.push(i);
  }
 
  return newArray;
}
```

## 7/02 


[https://www.codewars.com/kata/multiples-of-3-or-5/train/javascript]

```javascript
function solution(n){
let sum = 0;
for (let i = 3; i < n; i++){
  if(i % 3 === 0 || i % 5 === 0){
   sum += i;
   }
 }
 return sum;
}
```

[https://www.codewars.com/kata/sum-mixed-array/train/javascript]
```javascript
function sumMix(x){
let sum = 0;
for(let i = 0; i < x.length; i++){
if(typeof x[i] === 'string'){
  x[i] = Number(x[i]);
}
 sum += x[i];
}
return sum;
}
```

[https://www.codewars.com/kata/find-numbers-which-are-divisible-by-given-number/train/javascript]

```javascript
function divisibleBy(numbers, divisor){
const arr = [];
for(let i = 0; i < numbers.length; i++){
  if(numbers[i]% divisor === 0){
  arr.push(numbers[i])
}
  }
 return arr;
}
```

[https://www.codewars.com/kata/simple-fun-number-1-seats-in-theater/train/javascript]

```javascript 
function seatsInTheater(nCols, nRows, col, row) {
let blockedCl = (nCols-col)+1;
let blockedR = nRows-row;
return blockedCl * blockedR;
}

https://www.codewars.com/kata/return-the-day/train/javascript
function whatday(num) { 
  if(num === 0 || num > 7){
  return "Wrong, please enter a number between 1 and 7";
  }
  else switch (num){
  case 1: return "Sunday";
  break;
  case 2: return "Monday";
  break;
  case 3: return "Tuesday";
  break;
  case 4: return "Wednesday";
  break;
  case 5: return "Thursday";
  break;
  case 6: return "Friday";
  break;
  case 7: return "Saturday";
  break;
  }
}
```

[https://www.codewars.com/kata/remove-exclamation-marks/train/javascript]


```javascript 
function removeExclamationMarks(s) {
   let sNew = s.replace(/\!/g, '');
  return sNew;
}

https://www.codewars.com/kata/sum-even-numbers/train/javascript

function sumEvenNumbers(input) {
  let sum = 0;
  for(let i = 0; i < input.length; i++){
    if(input[i] % 2 === 0){
      sum += input[i]
    }
  }
  return sum;
}
```



[https://www.codewars.com/kata/sum-of-all-the-multiples-of-3-or-5/train/javascript]
```javascript
function findSum(n) {
let sum = 0;
  for(let i = 3; i <= n; i++){
    if(!(i % 3) || !(i % 5)){
    sum += i;
    }
  }
  return sum;
}
```

## 7/7 

[https://www.codewars.com/kata/reversing-a-string/train/javascript]
```javascript
function reverseString(str) {
let strNew = '';
for (let i = str.length-1; i >=0; i--){
 strNew += str[i];
}
  return strNew;
}
```

[https://www.codewars.com/kata/can-we-divide-it/train/javascript]

```javascript
function isDivideBy(number, a, b) {
if (!(number % a) && !(number % b)){ 
  return true;
  }
  else return false;
}
```

[https://www.codewars.com/kata/makeuppercase/train/javascript]

```javascript
function makeUpperCase(str) {
 return str.toUpperCase();
}
```

## 7/7 

[https://www.codewars.com/kata/simple-beads-count/train/javascript]
```javascript
function countRedBeads(n) {
let count = 0; 
  if (n < 2) {
  return 0;
  }
  else for (let i = 1; i < n; i++){
   count +=2;
  }
 return count;
}
```

[https://www.codewars.com/kata/string-repeat/train/javascript]
```javascript
function repeatStr (n, s) {
let sNew = '';
for (let i = 0; i < n; i++){
  sNew += s;
}
  return sNew;
}
```

[https://www.codewars.com/kata/create-phone-number/train/javascript]
```javascript
function createPhoneNumber(numbers){
  var format = "(xxx) xxx-xxxx";
  
  for(var i = 0; i < numbers.length; i++)
  {
    format = format.replace('x', numbers[i]);
  }
  
  return format;
}
```

## 7/11

[https://www.codewars.com/kata/ordering-the-words/train/javascript]

```javascript
function orderWord(s){
if(!s || s.length === 0)
{
 return "Invalid String!";
}
else{ let sNew = '';
let arr = []
 for(let i = 0; i < s.length; i++){
   arr.push(s[i])
 }
  arr.sort();
 for(let i = 0; i < arr.length; i++){
  sNew += arr[i];
 }
 return sNew;
}
}
```

[https://www.codewars.com/kata/filter-coffee/train/javascript]

```javascript
function search(budget, prices) {
let pr = [];
let prStr = '';
for (let i = 0; i < prices.length; i++){
  if(budget >= prices[i]){
  pr.push(prices[i]);
  }
}
 prStr = pr.sort((a, b) => a-b).join();  
 return prStr;
}
```

[https://www.codewars.com/kata/spongebob-meme/train/javascript]
```javascript
function spongeMeme(sentence) {
let str = '';
 for(let i = 0; i < sentence.length; i++){
  if (i % 2 === 0)
  {
  str += sentence[i].toUpperCase();
  }
  else str += sentence[i].toLowerCase();
 }
  return str;
}
```

 olgab/newKatas: 
 
 [https://www.codewars.com/kata/numerical-palindrome-number-1/train/javascript]
   
   ```javascript 
   function palindrome(num){ 
    if(num < 0 || typeof num === 'string')
    {
     return 'Not valid';
    }
    else {
     let str = num.toString().split('');
     let strLen = str.length/2; 
     for(let i = 0; i <= strLen; i++){
       if(str[i] !== str[str.length-1-i])
          {
          return false;
          }
       }
     }
     return true;  
    }
   ```
   
   [https://www.codewars.com/kata/smallest-value-of-an-array/train/javascript]
   ```javascript
   function min(arr, toReturn){
   let min = arr[0];
     for(let i = 1; i < arr.length; i++){  
       if(arr[i] < min){
        min = arr[i];
       }
     }
     if(toReturn === 'value') 
     {
       return min;
     }
     else if(toReturn === 'index')
     {
       return arr.indexOf(min);
     }
    }```



master solutions:

[https://www.codewars.com/kata/reverse-a-number/train/javascript]

```javascriptfunction reverseNumber(n) {
 let reversed = n.toString().split('').reverse().join('');
 return parseInt(reversed)* Math.sign(n);
}
```

## 7/13
 
 [https://www.codewars.com/kata/find-the-calculation-type/train/javascript]
 
 ```javascript
 https://www.codewars.com/kata/count-by-x/train/javascript
 function countBy(x, n) {
   var z = [];
   for(let i = x; i <= x*n; i += x){
     z.push(i);
     }
   return z;
 }
 ```
 
 [https://www.codewars.com/kata/reversed-strings/train/javascript]
 
 ```javascrip
 function solution(str){
 let strN = '';
   for(let i = str.length-1; i >=0; i--){
   strN += str[i];
   }
 return strN;
 }```
 
 [https://www.codewars.com/kata/sum-of-all-the-multiples-of-3-or-5/train/javascript]
 
 ```javascript
 function findSum(n) {
 let sum = 0;
   for(let i = 3; i <= n; i++){
     if(!(i % 3) || !(i % 5)){
     sum += i;
     }
   }
   return sum;
 }
 ```
 
 
## 7/16

[https://www.codewars.com/kata/calculate-average/train/javascript]

```javascript
function find_average(array) {
let sum = 0;
  for (let i = 0; i < array.length; i++){
    sum += array[i]
  }
  return sum/array.length;
}
```

[https://www.codewars.com/kata/sum-all-the-arrays/train/javascript]

```javascript
function arraySum(arr) {
let sum = 0;
let sum1 = 0;
  for(let i = 0; i < arr.length; i++){
    if(typeof arr[i] === "number"){
    sum += arr[i];
    }
    if(typeof arr[i] === "object"){
    for(let j = 0; j < arr[i].length; j++){
     sum1 += arr[i][j];
    }
```

[https://www.codewars.com/kata/merge-two-sorted-arrays-into-one/train/javascript]
    ```javascript
    function mergeArrays(arr1, arr2) {
    const arr = [];
    const arrN = [];
      for(let i = 0; i < arr1.length; i++){
      arr.push(arr1[i]);
      }
      for(let i = 0; i < arr2.length; i++){
      arr.push(arr2[i]);
      }
      for(let i = 0; i < arr.length; i++){
        if (arr.indexOf(arr[i]) >= i){
         arrN.push(arr[i]);     
        }
      }
        return arrN.sort((a,b) => a-b);
    }```

## 7/19 

[https://www.codewars.com/kata/find-the-missing-element-between-two-arrays/train/javascript]
```javascriptfunction findMissing(arr1, arr2) {
  arr1.sort((a,b)=> a-b);
  arr2.sort((a,b)=> a-b);
  let a; 
  for(let i = 0; i < arr1.length; i++){
    if (arr1[i] !== arr2[i]) {
     return arr1[i];
    }
  }
}
```

[https://www.codewars.com/kata/simple-transposition/train/javascript]
 ```javascript
 function simpleTransposition(text) {
 let row1 = '';
 let row2 = '';
 for (let i = 0; i < text.length; i++){
  if (!(i % 2)){
  row1 += text[i];
  }
  else if(i % 2){row2 += text[i];}
  }
 return row1 + row2;
 }
 ```
 
 [https://www.codewars.com/kata/sum-of-positive/train/javascript]
 ```javascript
 function positiveSum(arr) {
 return arr.reduce((acc, el) => {
  return el > 0? acc + el : acc;}, 0);
 }
```


##7/20

[https://www.codewars.com/kata/sum-even-numbers/train/javascript]
```jaavscript
function sumEvenNumbers(input) {
  let sum = 0;
  for(let i = 0; i < input.length; i++){
    if(input[i] % 2 === 0){
      sum += input[i]
    }
  }
  return sum;
}
```

[https://www.codewars.com/kata/remove-exclamation-marks/train/javascript]
```javascript
function removeExclamationMarks(s) {
   let sNew = s.replace(/\!/g, '');
  return sNew;
}
```

[https://www.codewars.com/kata/return-the-day/train/javascript]
```javascript
function whatday(num) { 
  if(num === 0 || num > 7){
  return "Wrong, please enter a number between 1 and 7";
  }
  else switch (num){
  case 1: return "Sunday";
  break;
  case 2: return "Monday";
  break;
  case 3: return "Tuesday";
  break;
  case 4: return "Wednesday";
  break;
  case 5: return "Thursday";
  break;
  case 6: return "Friday";
  break;
  case 7: return "Saturday";
  break;
  }
}
```

## 7/21
[https://www.codewars.com/kata/find-numbers-which-are-divisible-by-given-number/train/javascript]

```javascript
function divisibleBy(numbers, divisor){
const arr = [];
for(let i = 0; i < numbers.length; i++){
  if(numbers[i]% divisor === 0){
  arr.push(numbers[i])
}
  }
 return arr;
}
```

[https://www.codewars.com/kata/sum-mixed-array/train/javascript]

```javascript
function sumMix(x){
let sum = 0;
for(let i = 0; i < x.length; i++){
if(typeof x[i] === 'string'){
  x[i] = Number(x[i]);
}
 sum += x[i];
}
return sum;
}
```

[https://www.codewars.com/kata/multiples-of-3-or-5/train/javascript]

```javascript
function solution(n){
let sum = 0;
for (let i = 3; i < n; i++){
  if(i % 3 === 0 || i % 5 === 0){
   sum += i;
   }
 }
 return sum;
}```


## 7/22

[https://www.codewars.com/kata/sum-of-positive/train/javascript]

```javascript
function positiveSum(arr) {
return arr.reduce((acc, el) => {
 return el > 0? acc + el : acc;}, 0);
}
```

# 7/23

[https://www.codewars.com/kata/unfinished-loop-bug-fixing-number-1/train/javascript]

```javascript
function createArray(number){
  var newArray = [];
  
  for(let i = 1;  i <= number; i++){
    newArray.push(i);
  }
  return newArray;
```
[https://www.codewars.com/kata/reverse-list-order/train/javascript]

```javascript
function reverseList(list) {
const arr = [];
  for(let i = list.length-1; i >= 0 ; i--){
  arr.push(list[i]);
  }
  return arr;
}

```

# 7/11/20

Multiples of Two
```javascript
function multiply(a, b) {
  return a * b;
}
```

Find Multiples of a Number
```javascript
function findMultiples(integer, limit){
  const arr = [];
  for(i = integer; i <= limit; i++){
    if(i % integer === 0){
      arr.push(i)
  }
    }
    return arr;
}
```

Training JS #2: Basic data types--Number
[https://www.codewars.com/kata/571edd157e8954bab500032d/solutions/javascript]
```javascript
var v1=50;v2=100,v3=150,v4=200,v5=2,v6=250
function equal1(){
  var a=v1   
  var b=v1   
  return a+b;
}
//Please refer to the example above to complete the following functions
function equal2(){
  var a=v4   //set number value to a
  var b=v2   //set number value to b
  return a-b;
}
function equal3(){
  var a=v1   //set number value to a
  var b=v5   //set number value to b
  return a*b;
}
function equal4(){
  var a=v4   //set number value to a
  var b=v5   //set number value to b
  return a/b;
}
function equal5(){
  var a=v6   //set number value to a
  var b=v3   //set number value to b
  return a%b;
}
```

Grasshopper - Messi Goals
```javascript
let laLigaGoals = 43;
let championsLeagueGoals = 10;
let copaDelReyGoals = 5;

let totalGoals = laLigaGoals + championsLeagueGoals + copaDelReyGoals;
```