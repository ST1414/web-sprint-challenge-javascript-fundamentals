# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a range of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge. 

## Introduction

The index.js file contains all of your challenges. Please review it in full before answering the questions. If you complete the stretch goals please leave them in your file but commented out so that they do not affect the MVP tasks 

In meeting the minimum viable product (MVP) specifications listed below, you should have all tests passing. You can console.log to check your work and ensure you are submitting the correct results 

### Commits

Set up codegrade early and commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question.)
Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. Explain the differences between `.map`, `.reduce` and `.filter` and describe a use case for each. 
    <!-- 
        MAP -- We use map to perform a task on every element, and return the results into a new array. This could include: copying specific pieces of data from each array element or performing a mathematical function.  You are also able to embed conditions in the call back function passed to map, so that the task is only performed on certain elements

        REDUCE -- We use reduce to perform a calculation on a specific field and to return a single number.  For example, in an array of State objects, totalling the population of states in a specific region.

        FILTER -- We use filter to return an array of only the elements which pass a condition.
    -->

2. Explain the difference between a callback and a higher order function.
    <!-- 
        HIGHER ORDER FUNCTION -- A higher order function accepts a function as a parameter.
        CALLBACK FUNCTION  -- A callback function, is a function passed to a higher order function, as a parameter
     -->

3. Explain what a closure is.
    <!-- 
        CLOSURE -- Is when an inner function, reaches into an outer function, to grab a value defined in that outer function.  A closure will create a memory of that inner functions lexical environment, meaning it will have access to that outer function's value, after that outer function's call has ended.
     -->

4. Describe the four principles of the 'this' keyword.
    <!-- 
        NEW -- A new binding occurs when a constructor function is called (via the new keyword).  Anything passed to the constructor and assigned to properties defined with {this} are bound to the newly created object

        IMPLICIT -- An implicit binding happens when calling a method, where this is bound to the object making the method call (i.e., to the left of the dot).  This is the most common binding principle.  E.g., objectName.functionName( ) ... this would apply to {objectName} because it is to the left of the dot

        EXPLICIT -- When we use .call( ), apply( ), or bind ( ); which are functions built into the Function prototype.  Each method has its own use cases, but all are required to explicitly bind a function that is external to the object.  Call( ) will run the function immediately and requires each parameter (if required) passed independently.  Apply( ) is the same as call but you can pass the arguments as an array.  Bind( ) allows you to create the new function on the object but to not run it immediately.

        WINDOW -- When this is used and JS is not given a reference to how to use it.  JS will then bind to the Window object.
     -->

5. Why do we need super() in an extended class?
    <!-- 
        super( ) replaces the call( ) function in a constructor function. Super tell JS that when an object is being created, that extends another object, to go and get the properties associated to that parent object.  The argument passed will then populate those keys accordingly
     -->

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:


1. Fork the repo
2. Clone your forked version of the repo
3. cd into your repo and create a branch with your first and last name
4. open the terminal in your vs code and type `npm install`
5. next type `npm run test` in your terminal
6. Complete your work making regular commits, once you have all your tests passing and you are ready to submit your work please see canvas for instructions on how to submit

### Testing & Debugging

Open a second terminal inside of your project by clicking on the split terminal icon
![alt text](assets/split_terminal.png "Split Terminal")

Inside of your second terminal type `npm start` 
![alt text](assets/npm_start.png "type npm start")

You will be running your tests in one terminal and debugging in the other. As you work on your code you should make use of `console.log` to check your progress and debug.
![alt text](assets/tests_debug_terminal_final.png "your terminal should look like this")

### Task 2: Project Requirements (MVP)

You must complete all tasks inside of `index.js` and answer the questions above.

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Resources
 
 [Sprint Challenge Study Guide](https://www.notion.so/lambdaschool/Unit-1-Sprint-3-Study-Guide-033a9a00659a4ef98c12eb97e49a6110)

## Submission format

Please submit your project via codegrade by following [these instructions](https://www.notion.so/lambdaschool/Submitting-an-assignment-via-Code-Grade-A-Step-by-Step-Walkthrough-07bd65f5f8364e709ecb5064735ce374)

