---
layout: essay
type: essay
title: We All Have Standards
date: 2017-02-08
labels:
  - Coding Standards
  - Software Engineering
---

## ESLint

<img class="ui medium right rounded floated image" src="/images/coding_standards-eslint.png">

ESLint has been extremely useful so far. It has helped me understand the language better, and identify ways to write my code more efficiently. Since it shows errors for redundancy and whether a variable should be declared with `let` or `const`, I have been trying to remember these errors, and write my code so that they will not show up the first time. Additionally, having a coding standard can vastly improve readability in a project. Some of the coding standards are small and seem meaningless. Some that come to mind are: no trailing spaces after semicolons or hanging brackets, a space between an `if` and its condition, and a space between a functions arguments and its starting bracket. However, these small details keep the code clean so that when you come back to the project or someone else works on the project, they can easily understand what was written.

## Learning the Language

Having a coding standard can help someone learn a new programming language, but only if it is working with an IDE that actively highlights the errors. Without an IDE that points out these coding standard errors, identifying and correcting mistakes can be troublesome. For instance, if you're still learning a language like Javascript, you would not be aware of whether you should be declaring variables using _let_ or _const_. Without an IDE to show you the mistakes, you might write the following code:
```    
  ...
  let array = [];
     
  array.push(0);
  array.push(1);
  array.push(2);
  ...
```
Coming from a C/C++ background, I assume `array` should be declared with `let` because it is changing. However, `let` is for when a variable is reassigned, which does not happen. IntelliJ will show an ESLint error saying that `let` needs to be changed to `const`. There are a lot of small details that a beginner can miss if not using a coding standard-IDE combination. By ESLint standards, there needs to be a newline at the end of the program, or it will report an error. From experience, I can say that having a coding standard does help a beginner learn a programming language since ESLint has done that for me with Javascript.

<center>
<img class="ui large rounded image" src="/images/coding_standards-newline.png">
</center>

## Improving Group Productivity

In short programs like we have been creating in class, the importance of coding standards is not as apparent. However, on large projects with thousands of lines of code and multiple collaborators, having a set coding standard can help the project move along nicely. This allows separate groups to work within the same files or on related functions, and still understand each others work since they are following the same style and syntax. In a project where the source code is available for viewing by the public, following a coding standard can keep uniformity throughout the code. Although code where one team is using snake_case variable naming and in-line curly brackets and the other
<img class="ui medium right rounded floated image" src="/images/coding_standards-naming.png">
group is using camelCase variable naming and C-style brackets may work, it may not look very appealing or easily read by the people interested in joining or endorsing the project. 
