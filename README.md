<!DOCTYPE html>
<html>
<head>
	<title>JavaScript Lab</title>
</head>
<body>
	<script>
        // Task 1: Variable Declaration and Math operations
        var num1 = 10, num2 = 5;
        console.log("Addition: ", num1 + num2);
        console.log("Subtraction: ", num1 - num2);
        console.log("Multiplication: ", num1 * num2);
        console.log("Division: ", num1 / num2);
    // Task 2: String manipulation and Concatenation
        var firstName = "Jordan", lastName = "Dale";
        console.log("Full Name: ", firstName + " " + lastName);

   // Task 3: Using "let" and "var" to declare Variables
        let x = 5;
        var y = 10;
        console.log("x: ", x);
        console.log("y: ", y);
        x = 15;
        y = 20;
        console.log("x after reassignment: ", x);
        console.log("y after reassignment: ", y);

  // Task 4: Increment and Decrement Operators
        var counter = 0;
        counter++;
        console.log("Counter value: ", counter);
        
  // Task 5a: Type Conversion and Coercion
        var numStr1 = prompt("Enter first number:");
        var numStr2 = prompt("Enter second number:");
        var sum = Number(numStr1) + Number(numStr2);
        console.log(numStr1 + " + " + numStr2 + " = " + sum);
