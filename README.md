# Sprint Challenge: JavaScript Fundamentals

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a survey of problems. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied variables, functions, object literals, arrays, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a survey of JavaScript problems.

## Instructions

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your TL and Instructor in your cohort help channel on Slack. Your work reflects your proficiency in JavaScript fundamentals.

You have three hours to complete this challenge. Plan your time accordingly.

## Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons) and your team lead.

## Description

You will notice there are several JavaScript files being brought into the index.html file.  Each of those files contain JavaScript problems you need to solve.  If you get stuck on something, skip over it and come back to it later.

In meeting the minimum viable product (MVP) specifications listed below, you should have a console full of correct responses to the problems given.

## Self-Study Questions

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your team lead

1. Describe the biggest difference between `.forEach` & `.map`.

    .forEach will run a for loop for each item inside of an array, .map will return an array with the specified items you want

2. What is the difference between a function and a method?

    a function is a piece of code that does something specific when it is called. a method is a function that belongs to a specific object and is called in reference to that object.

3. What is closure?

    closure is best described as a full account of each item in a line of code. Where the variables are where the parameters are where the arguments are. It is being able to see the function as well as what the function is refering to

4. Describe the four rules of the 'this' keyword.

  1, Window/global object binding when 'this' is used on the top level of code it will refer to the window it is in. generally it isnt used this way and is often disabled within code editors. 2, Implicit binding is when this refers directly to the parent object it is in. 3, new bindings are when this refers to an object that will exist its used within the context of a constructor function which will creat a new object changing the new binding to an implicit binding. 4, Explicit binding when using 'this' in this context we are using a call or apply method to directly refer to another object. we are explicitly stating the object we want that 'this' will refer to.

5. Why do we need super() in an extended class?

    super() allows us to pass arguments to the parent class without having to rewrite keys for those values

## Project Set up

Follow these steps to set up and work on your project:

- [ x] Create a forked copy of this project.
- [ x] Add TL as collaborator on Github.
- [x ] Clone your OWN version of Repo (Not Lambda's by mistake!).
- [x ] Create a new Branch on the clone: git checkout -b `<firstName-lastName>`.
- [x ] Create a pull request before you start working on the project requirements.  You will continuously push your updates throughout the project.
- [ x] You are now ready to build this project with your preferred IDE
- [ x] Implement the project on your Branch, committing changes regularly.
- [ x] Push commits: git push origin `<firstName-lastName>`.

Follow these steps for completing your project:

- [ x] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's  Repo).
- [ x] Add your team lead as a Reviewer on the Pull-request
- [ x] TL then will count the HW as done by  merging the branch back into master.


## Minimum Viable Product

Your finished project must include all of the following requirements:

**Pro tip for this challenge: If something seems like it isn't working locally, copy and paste your code up to codepen and take another look at the console.**

## Task 1: Objects and Arrays
Test your knowledge of objects and arrays. 
* [ x] Use the [objects-arrays.js](challenges/objects-arrays.js) link to get started.  Read the instructions carefully!

## Task 2: Functions
This challenge takes a look at callbacks and closures as well as scope. 
* [ x] Use the [functions.js](challenges/functions.js) link to get started. Read the instructions carefully!

## Task 3: Prototypes
Create constructors, bind methods, and create cuboids in this prototypes challenge.
* [ x] Use the [prototypes.js](challenges/prototypes.js) link to get started. Read the instructions carefully!

## Task 4: Classes
Once you have completed the prototypes challenge, it's time to convert all your hard work into classes.
* [ x] Use the [classes.js](challenges/classes.js) link to get started. Read the instructions carefully!

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Stretch Problems

There are a few stretch problems found throughout the files, don't work on them until you are finished with MVP requirements!
