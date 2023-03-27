# Complete Lox Interpreter

## DUE: April 11 by 2:30pm

## Table of Contents

- [Introduction](#introduction)

- [Learning](#learning)

- [Requirements](#requirements)

- [Assignment Assessment](#assignment-assessment)

- [Assistance](#assistance)

## Introduction

This assignment requires students to create a completed version of the first interpreter for the lox programming language by following Chapters 8 through 13 of the "Crafting Interpreters" textbook. You are to work in the lox team you have already set up for this lab. In addition to getting a working interpreter as it is implemented in the book, you are responsible for adding a feature/functionality-related extension to the interpreter and provide a complete documentation for the working interpreter in the README of the `lox_interpreter` repository. Furthermore, each team is invited to engage in a code walkthrough of a work-in-progress during the lab on April 4th and in a complete, working demonstration during the lab on April 11th with a TL and/or instructor.

You are responsible for storing all implementation for this lab in your team's `lox_interpreter` repository. 

## Learning

To enhance your understanding of the concepts and code of this laboratory assignment, you should carefully read [Chapters 8-13](https://craftinginterpreters.com/contents.html) in Crafting Interpreters.

## Requirements

1. Complete working version of the interpreter from the textbook with addition of proper comments.
2. Small enhancement to the interpreter.
3. Complete documentation.
4. Participation in the work-in-progress walkthrough and complete working demo.

### Working and Properly Commented Interpreter

- After verifying complete implementation of [Evaluating Expressions](https://craftinginterpreters.com/evaluating-expressions.html), which was Activity 12, follow  [Chapter 8 in Crafting Interpreters](https://craftinginterpreters.com/statements-and-state.html) textbook to add statements and states to your interpreter.
- Then, follow [Chapter 9](https://craftinginterpreters.com/control-flow.html) to add control flow structures and [Chapter 10](https://craftinginterpreters.com/functions.html) to add functions. **This is where you should be at the minimum before in-progress walkthrough.**
- And finally, follow [Chapter 11](https://craftinginterpreters.com/resolving-and-binding.html) to adjust scoping and binding, and Chapters [12](https://craftinginterpreters.com/classes.html) and [13](https://craftinginterpreters.com/inheritance.html) to add object-oriented functionality.
- Test your interpreter on a [variety of `lox` programs](https://github.com/munificent/craftinginterpreters/tree/master/test).
- For all new Java classes add standard Javadoc comments before each class and each method, and single line comments to explain lines of code

### Enhancements

Add one enhancement (make changes or additions to the code) to make the interpreter your own. This enhancement should not be purely cosmetic, as others have mostly been, but it should try to add additional feature or functionality, albeit small, to the interpreter.

### Documentation

For this part of the assignment, you are to finish the section in the README so that, at the minimu, it has information about (see Section 13.4):

- Scanning
- Parsing
- Scope
- Expression Evaluation
- Control Flow
- Functions
- Closures
- Static variable resolution and error detection
- Classes
- Constructors
- Fields
- Methods
- Inheritance

The organization of the README is up to you and addition of new visualization is not required.

### Walkthrough and Demo

During our next lab on April 4th, each team will demonstrate their work-in-progress interpreter by participating in a code walkthrough. Code walkthrough is an informal analysis process with a goal of identifying defects within the code. In this case, code walkthrough will also be used to assess the understanding of the code by the team members and to ensure team is making sufficient progress. You are expected to complete Chapters 8-10 by next lab, at the minimum. 

Similar to previous sessions, teams can assign specific members to lead the review of the certain portion of the code, however questions can be directed to anyone on the team. 

Then, during the lab session on April 11th, teams will be invited to demonstrate the completed version of their interpreter and to present their enhacenment contribution. 

## Assignment Assessment

GitHub Actions is not used in this assignment. The grade that a student receives on this assignment will have the following components. All components of the grade will be assessed manually by the instructor and the technical leaders. The grades will be assessed on individual basis and grade reduction will be given to team members who do not sufficiently contribute to this lab during each of two weeks of the lab session.

- **Mastery of Verbal Explanation [up to 35%]:** Students will receive a portion of their grade when their explanations presented during the walkthrough reveal a thorough understanding of the code. Every member of the team is expected to understand every line of code being presented. The reviewer reserves to question any member of the team to assess their understanding.

- **Mastery of Technical Writing [up to 25%]:** Students will also receive a portion of their grade when the documentation reveals a proficiency of both writing skills and technical knowledge. 

- **Mastery of Technical Knowledge and Skills [up to 40%]:** Students will receive a portion of their assignment grade when their lab solution reveals that they have mastered all of the technical knowledge and skills developed during the completion of this assignment. As a part of this grade, the instructor will assess aspects of the project including, but not limited to, the completeness and correctness of the parser, the required extension, and contributions of each student to the project on GitHub.

All grades for this project will be reported through a student's gradebook GitHub repository.

## Assistance

If you are having trouble completing any part of this project, then please talk with the course instructor or technical leaders during the laboratory session. Alternatively, you may ask questions in the Discord channel for this course. Finally, you can schedule a meeting during the course instructor's office hours.
