![General Assembly Logo](http://i.imgur.com/ke8USTq.png)

# Assessment for JavaScript Fundamentals

You have 20 minutes

## Instructions

Fork, clone, and npm install.

Follow the prompts below and complete each question.  You may use any resource, other than someone else in the classroom, to help you complete this assessment.

You should save your answers in this README.md file.

# Question 1

```js
var a = 2;
var b = 3;
a = b;
```

After this code executes, what are the values of a and b? Please explain your answer.

<!-- After this code executes, the value of a is 3 and the value of b remains 3. This is because a is reassigned to b which has a value of 3 and b is unchanged so its value remains 3. -->

## Question 2

```js
var c = 5;
var d = 2;
c = c + d;
```

After this code executes, what is the value of c?  Please explain what the last line of this program `c = c + d;` means.

<!-- The value of c is now 7. The last line 'c = c + d;' means that c is being assigned to the value of the evaluation (c + d) which evaluates to 5+2, so c is assigned to the value 7. -->

## Question 3

```js
var x = 4;
var y = 3;
x = y;
y = 10;
```

After this code executes, what are the values of x and y?  Please explain your answer.

<!-- After this code executes, the value of x is 3 and the value of y is 10. The value of x is reassigned to 3 after the line 'x = y;' because y's value is 3. The value of y is reassigned to 10 with the assignment 'y = 10;'. -->

## Question 4

```js
var weather;
weather = "sunny";
weather === "sunny";
```

What are the values of these expressions?  Explain your answers.

<!-- The first expression creates the variable 'weather'. The second expression assigns the string 'sunny' to the variable weather. The last expression is one of boolean equality and evaluates to true because the variable weather is 'sunny'. -->

## Question 5

```js
var howMuchILikeSushi = 2;

if (howMuchILikeSushi >= 3) {
  console.log("sushi is delicious");
}

if (x > 0) {
  console.log("sushi is tasty");
}
```

Imagine that you take the code from this question, save it to a file called `food.js`, and run `node food.js` in your Terminal.

What would be the output? Explain your answer.

<!-- You would get an error returned because x in undefined. This code only defines the variable howMuchILikeSushi. It doesn't define the variable x, so the second if statement can't be executed. -->

## Question 6

```js
var howMuchILikeSushi = 2;

if (howMuchILikeSushi > 0) {
  console.log("sushi is tasty");
} else if (x >= 3) {
  console.log("sushi is delicious");
} else {
  console.log("I don't like sushi");
}
```

Imagine that you take the code from this question, save it to a file called `sushi.js`, and run `node sushi.js` in your Terminal.

What would be the output? Explain your answer.

<!-- If you ran this code, the output would read 'sushi is tasty'. Unlike the previous question, x being undefined does not create an error output because the else if statement that it is used in is never evaluated. Because howMuchILikeSushi = 2 and 2 > 0, the interpreter stops after the first if statement and returns 'sushi is tasty'. It doesn't even go on to evaluate the else if statement which would return the error for having an undefined variable. -->

## Question 7

```js
//We'll learn about require later in the course
var ask = require('./ask.js');

var answer = 'not empty';

while (answer !== '' && answer !== 'SeCrEt') {
  answer = ask("Guess my secret? ");
}
```

Imagine that you take the code from this question, save it to a file called `name.js`, and run `node name.js` in your Terminal.

What would you have to type to exit the while loop?  Explain your answer.

<!-- You would have to type SeCrEt to exit the while loop or hit enter with nothing typed. The while loop would continue so long as your answer wasn't an empty string or SeCrEt. So to escape, you would either type nothing and hit enter or type SeCrEt. -->

---

Commit and push your changes.

Submit a pull request.
