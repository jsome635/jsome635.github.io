---
layout: essay
type: essay
title: langArr.push("JavaScript");
date: 2018-01-19
labels:
  - ICS 314
  - JavaScript
  - Software Engineering
---

During this past week of ICS 314, we learned the basics of JavaScript: variable declarations, function declarations, and many other various things. Coming into this class with experience in C and C++, most of the syntax and keywords are familiar, and it was not very difficult to get used to JavaScript. We do have Workout of the Day (WOD), a quick coding challenge, at the end of the week to test out the skills that we picked up. I was stressed heading into the WOD, and feared the worst. Since I am familiar with languages similar to JavaScript, I was able to quickly write a block of code that output a result close to what was expected. A quick fix to the order of my if-else statements solved my problems, and the WOD was over for me in a few minutes. JavaScript, based on the things I have learned this week, is easy for me to write, and can do some interesting things. As for the WODs, I thought that it was a quick, fun challenge, and looking forward to when they become increasingly difficult.

## Redefining the Old and Introducing New Ideas

Learning JavaScript was interesting because it deals with a handful of things differently than C, C++, or Java. Since I have been programming in C and C++ for about 2 years, it was difficult to get out of the habit of declaring a variable as one datatype. JavaScript lets variables be whatever datatype it needs to be, something I wish at times was possible in C or C++. A corollary of this is that a single array can store data of different datatypes. Additionally, because of my experience with C and C++, I was so used to fixed-size arrays. I was surprised while I was going through <a href="https://www.freecodecamp.org/">the JavaScript tutorial</a> to learn that it is possible to simply push and unshift data onto the array. To do something similar in C or C++, you need to used stacks, queues, or linked lists and struggle with managing the data and all the pointers. Arrays in JavaScript are much more flexible than arrays, stacks, queues, and linked lists in C and C++. I look forward to learning more of these simple differences that JavaScript provides compared to other languages.

<center>
  <img class="ui center rounded image" src="/images/javascript1/javascript1-push.png">
  <figcaption>Tutorial for pushing data onto arrays.</figcaption>
</center>
<br>/
Over this week, I learned two new things about JavaScript. During our <a href="http://courses.ics.hawaii.edu/ics314s18/morea/javascript-1/danny-wod-js1-kl2.html">practice WOD</a>, the teaching assistant (TA) showed us a new way to iterate through a for loop if the condition of the loop involves the length of the array. I have always known for loops to be written as:

```
  for(count = 0; count < array.length; count++){
    ...
  }
```

or something similar. However, as seen in the <a href="https://jsfiddle.net/jsome635/a7LbLzgq/">solution of the practice WOD</a>, the TA wrote:

```
  for(let food of foodList){
    ...
  }
```

<center>
  <img class="ui medium rounded image" src="/images/javascript1/javascript1-for.png">
</center>
<br/>
Another interesting that I learned is that you can use regular expressions to search and manipulate strings. When learning C and C++, we needed to make functions to do these operations. Even if these two features end up being unimportant and not frequently used, they allow us to program in JavaScript more efficiently, and our end code will be more understandable for anyone who has to debug or read our code.

## Thoughts on Athletic Software Engineering

Even though it is only the second week of the Spring semester, I am beginning to feel the stress that comes with this style of learning. Between other classes, projects, commuting, and personal life, it is difficult to do everything that I would like to. However, I do enjoy this learning style and hope that it will work out in the end. This method of learning makes sense to me, what good will listening to a professor talk about code do for me? Personally, I do not think the home practice WODs really help prepare me for the actual WOD. It allows us to practice writing code, but cannot recreate the in-class or practice WOD. First, we can think a little longer about our solution at home than we can in-class. Additionally, if you are doing multiple attempts consecutive, any attempt after the first feels like you are simply reiterating the solution. As a result, I think that it is very important to attend at least one of the TA's practice WODs.

