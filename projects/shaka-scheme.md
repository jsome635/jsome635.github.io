---
layout: project
type: project
image: images/shaka-scheme-square.png
title: Shaka Scheme
permalink: projects/shaka-scheme
date: 2017-01-11
labels:
  - C++
  - Scheme
  - GoogleTest
  - GitHub
summary: University of Hawaii - Transpiler Project. Contributed as part of the Parsing/IO team to create a REPL for a basic Scheme interpretter using C++.
---

This project originally started off as a project to make a transpiler for Scheme using C++ for someone's Sernior Project. To complete this, the overall group was separated into three different teams: Core Systems, Parsing/IO, and Design and Testing. As part of the Parsing/IO team, we were to follow the Revised7 Report on Algorithmic Language Scheme (R7RS) to create rules on how to parse in the data given by the user. At the beginning of the project, the team did not recieve much guidance from the person leading the project, and made little to no progress on the project. Once he began to help the team more, we realized that the method for parsing that he had laid out for us had some flaws. The parser experienced many revisions throughout the semesters, and the team had to rewrite old functions that worked for the previous version of the parser. By the end of the semester, the result of our work is a basic Scheme interpreter.  Shaka Scheme could evaluate most of the standard procedures. Because of the unforeseen complexity of macros and other operations of the parser, it needed to be implemented during the continuation of the project which I did not take part of.

My primary contribution to the project was the coding of the rules that parsed strings and worked on the rules that parsed variables and conditional statements with some of the other members of the Parsing/IO team. Since we were coding functions to parse information, we also needed to create test cases to check if the information was parsed properly. One of the first test cases I wrote was to check if Tokenizer created the proper DataNode. The test cases made after the creation of Token and Tokenizer were done by all members of parsing to understand the power of Tokenizer and check if it behaved as expected. Later, I wrote similar test cases to check if the rule for parsing strings pushed a DataNode onto the tree. Another test case resting the same rule checked if the string contain by the DataNode pushed to the tree is the same as the string that was input. These two test cases ensure that the string rule parsed the input data properly to the tree. Near the end of the semester, I wrote a test case to check if the string was appended to the list. Much like the test cases written earlier, I also had to make a test case to check if the number stored in the list is the same as the one input. These two test cases was to test that the string rule worked the same as it did with the Tokenizer, but modified to use the list.

Since the project is has been reworked since the time I contributed to it, I am unsure if the code I had written still exists as part of the project. The current version of the project can be viewed at: <a href="https://github.com/uhmanoa-transpiler-project/shaka-scheme"><i class="large github icon "></i>uhmanoa-transpiler-project/shaka-scheme</a>
