---
layout: project
title: Shaka Scheme
permalink: projects/shaka-scheme/contributions
---

<div class="ui three item menu">
  <a href="/projects/shaka-scheme/overview" class="item">Overview</a>
  <a href="/projects/shaka-scheme/contribution" class="active item">Contribution</a>
  <a href="/projects/shaka-scheme/outcome" class="item">Outcome</a>
</div>

<h2>Contribution to the Project</h2>
<p>
My primary contribution to the project was the coding of the rules that parsed strings and worked on the rules that parsed variables and conditional statements with some of the other members of the Parsing/IO team. Since we were coding functions to parse information, we also needed to create test cases to check if the information was parsed properly. One of the first test cases I wrote was to check if Tokenizer created the proper DataNode. The test cases made after the creation of Token and Tokenizer were done by all members of parsing to understand the power of Tokenizer and check if it behaved as expected. Later, I wrote similar test cases to check if the rule for parsing strings pushed a DataNode onto the tree. Another test case resting the same rule checked if the string contain by the DataNode pushed to the tree is the same as the string that was input. These two test cases ensure that the string rule parsed the input data properly to the tree. Near the end of the semester, I wrote a test case to check if the string was appended to the list. Much like the test cases written earlier, I also had to make a test case to check if the number stored in the list is the same as the one input. These two test cases was to test that the string rule worked the same as it did with the Tokenizer, but modified to use the list.
</p>