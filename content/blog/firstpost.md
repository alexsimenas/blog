---
title: Simple Calculation.
description: Today I used Javascript to make a simple calculator.
date: 2023-11-17
tags:
  - another tag
---
Check my simple calculator on the link <a href="https://codepen.io/Alex-Simenas/pen/MWLEeJM?editors=1011">https://codepen.io/Alex-Simenas/pen/MWLEeJM?editors=1011</a>

## Javascript simple caltulator

Listen if you dont want to press a link then check it out code bellow.

```the code is
 function calculator(number1, number2, operator) {
  var result;

  switch (operator) {
    case '+':
      result = number1 + number2;
      break;
    case '-':
      result = number1 - number2;
      break;
    case '*':
      result = number1 * number2;
      break;
    case '/':
      result = number1 / number2;
      break;
    case '%':
      result = number1 % number2;
      break;
    default:
      return "Invalid operator";
  }

  return `${number1} ${operator} ${number2} = ${result}`;
}

var num1 = 10;
var num2 = 5;
var chosenOperator = '+';

var calculationMessage = calculator(num1, num2, chosenOperator);
console.log(calculationMessage);
```
