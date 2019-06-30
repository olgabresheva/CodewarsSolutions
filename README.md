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

master branch solution _(after a new brach has been created)_

master branch: solution V1m


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
