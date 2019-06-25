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
