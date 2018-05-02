---
layout: essay
type: essay
title: Design Patterns
date: 2018-05-01
labels:
  - Design Patterns
  - Software Engineering
---

## Design Patterns?

Briefly, design patterns in software engineering can be described as general solutions to frequent, recurring problems. Since I have a lot of experience with C or C++, design patterns reminds me of function declarations. The idea is that the programmer creates a function that can be used again later in another, similar situation rather than rewriting this block of code repeatedly. However, this comparison isn't the most accurate for design patterns because these functions are usually not completely-general solutions. For languages like Java or Javascript, there are more than a handful of methods that are included in the numerous available libraries, some of which are actual implementations of a design pattern.

## Design Patterns vs Algorithms

While watching the professor's videos (<a href='https://www.youtube.com/watch?v=Z2yjimK_MJU'>1</a>, <a href='https://www.youtube.com/watch?v=yP-t44HBCPQ'>2</a>)
and reading the <a href='https://sourcemaking.com/design_patterns'>brief introduction about design patterns</a>, there was not much distinction between design patterns and algorithms. This sort-of crash course on the topic left me confused, even slightly still as I am writing this. What is the difference between design patterns and algorithms? <a href='https://softwareengineering.stackexchange.com/questions/92179/does-it-make-sense-to-ask-what-is-the-difference-between-design-pattern-and-al'>This post on StackExchange</a> had some replies that explained the difference very well. One reply drew a likeness between design patterns and diagrams. Design patterns help outline or blueprint the your classes and methods in a way that works in a fluid, seamless manner. This same reply related algorithms to a list of steps, like a set of instructions to be followed for the desired outcome. This implies that algorithms require some sort of implementation (even if in pseudocode), whereas a design pattern does not.

<div>
    <img class="ui centered roundede image" src="../images/design-patterns/design-patterns-diagram.png">
    <img class="ui centered rounded image" src="../images/design-patterns/design-patterns-instructions.png">
</div>

## Unseen and Unbeknownst

In my final project for this class, we have been using some design patterns without explicitly realizing it. This is because many of the methods given by Javascript, Underscore, Semantic UI React, Meteor, and MongoDB implement different design patterns, and are just given to us without us understanding the actually code behind them. Like the professor's example project in video 2, this project also implements the publish-subscribe, observer, and singleton design patterns (among many others). The publish-subscribe data pattern has a publishers that send data to their subscribers without needing to know them distinctly. The observer design pattern re-runs code when a collection is updated or a variable is changed. This is present in our project in how the collections are found each time a change occurs to it. The use of the singleton design pattern is also similar to the professor's in that both projects create collection classes to help management from the server and client side of the project. Additionally, we use the iterator design pattern by utilizing the map method available with the Underscore library. This method helps use to sequentially access the elements in the arrays and collections in the project. Lastly, the state design pattern is also widely-used in the form of on-click methods bound to various buttons in the project; many of these buttons change the values of fields and the behavior of the state.