---
layout: project
title: Look 'n' Cook
permalink: projects/android-app/contribution
---

<div class="ui three item menu">
  <a href="/projects/android-app/overview" class="item">Overview</a>
  <a href="/projects/android-app/contribution" class="active item">Contribution</a>
  <a href="/projects/android-app/outcome" class="item">Outcome</a>
</div>

<p>
My main contribution to the app was creating the user interface. Overall, the layout was visually basic, but had much more complicated than it looks. The three boxes for user input were coded to format the data automatically to match the field being entered, such as monetary values or percentages. This was done using a TextWatcher class that was written to fit our needs, and manipulated the data that was given. It would clean the string of characters like dollar signs, percent signs, commas, and decimals; convert it to a double or integer depending on the field that was being changed; format it for currency or percentage; and output to the interface. In addition to being able to enter values by keyboard, alternative, easier ways for user input were also implemented. One of the alternatives implemented was allowing the use of drop-down menus—known in Android Studio as Spinners—to change the number of people paying or the tip percentage quickly. Additionally, my partner was learning how to implement the OCR library so it could work alongside the user interface. I worked with her to figure out a way to parse the data read by the OCR to the interface properly. Lastly, instead of including and “equals” or “calculate” button, our design called for the tip calculator to calculate everything in real-time. After a lot of struggling, this was done by allowing our TextWatcher to access carefully selected public variables and methods in the main activity. By allowing the TextWatcher access this information, it could change the outputs shown on the interface while it formats the data entered by the user.
</p>
