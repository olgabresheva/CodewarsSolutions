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