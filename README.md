alert("Hello! Wellcome to my website");
var myName = prompt("What's your Name?");
console.log(myName);
var num1 = 3;
var num2 = 5;
console.log(num + num2); //3 + 5

//5 legal variable bellow:
var legal; // single word variable
var legalName; // double word variable camel casing
var legal_name; // double word space variable using underscore
var legal$name; // double word variable with $ sign
var legalStringName; // 3 words variable

//5 illegal variable bellow:
var Illegal; // can't use 1st letter capital in single word
var illegalname; // can't use second word 1st letter small
// var illegal Name; // shouldn't have space in variable only with underscore
var IllegalName; // always 1st letter should be small even using double words
// var Illegal name; // shouldn't use grammer of English

console.log(num + num2); // add
console.log(num - num2); // subtract
console.log(num * num2); // multiple
console.log(num / num2); // division

//Modulus (%) Operator
var num = +prompt("Enter a number I will check it is even or odd");
if (num % 2 == 0) {
  console.log(num + " is even");
} else {
  console.log(num + " is odd");
}

//  Pre/Post Increment & Decrement Operators
console.log(++num); // pre increment = It will add 1 before display and display added value
console.log(num--); // post decrement = It will subtract 1 after display
console.log(num++); // post increment = It will increase 1 after display
console.log(--num); // pre decrement = It will subtract 1 before display

// Concatenating Text Strings
var fName = "Prem";
var eName = "Kumar";
console.log(fName + " " + eName); // This will add Umer and Soomro display will be Umer Soomro

// Prompts
var color = prompt("Your favorite color?");
console.log("You favorite color is " + color);

// if Statements
if (num == 10) {
  console.log("true");
}

// Comparison Operators
if (5 == "5") {
  // == doesn't check data type often === check data type
  console.log("true");
} else if (5 === "5") {
  //=== check data type
  console.log("true");
} else {
  console.log("false");
}

/*Ask the user for marks and show grade based on:

80–100 → “A Grade”
60–79 → “B Grade”
40–59 → “C Grade”
Below 40 → “Fail”*/

var percent = +prompt("WHat is your percentage");
if (percent >= 80) {
  console.log("A");
}
if (percent >= 60) {
  console.log("B");
}
if (percent >= 40) {
  console.log("C");
} else {
  console.log("Fail");
}

// Bonus quiz
var one = +prompt("Enter First number");
var operator = prompt("Enter an operator (+, -, *, /):");
var two = +prompt("Enter second number");
var result;
if (operator === "+") {
  result = one + two;
} else if (operator === "-") {
  result = one - two;
} else if (operator === "*") {
  result = one * two;
} else if (operator === "/") {
  result = one / two;
} else {
  result = "Invalid operator";
}
console.log("Result = ", result);
