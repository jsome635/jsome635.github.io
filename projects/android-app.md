---
layout: project
type: project
image: images/android-app-square.jpg
title: Android App Development - Tip Calculator
permalink: projects/tipcalculator
date: 2017-08-21
labels:
  - Java
  - Android Studio
summary: My partner and I developed an Android app that dynamically calculated tip from input given by the user,parsed in by OCR, or selected in dropdown menus.
---

For this project, my partner and I aimed to create a tip calculator for the people who wanted to get the cost of tips quickly or those who struggled to calculate tip on their own. To make this app more appealing than calculating tip yourself or using a different app, we attempted to implement the library for Optical Character Recognition (OCR) to enter data by reading an image of the receipt. By the end of the project, the app reflected mostly what we had planned out for the project. There were still some minor bugs. Two main bugs was that the OCR activity did not go back to the tip calculator’s main activity after reading the image, and the output displayed more decimal places than necessary for monetary values. Additionally, we wanted to add a feature that such as saving and viewing past entries so that a user can review and remember their expenses.


<img src="/images/android-app-ocr.png">
<center>General test of OCR for correct parsing.</center>

My main contribution to the app was creating the user interface. Overall, the layout was visually basic, but had much more complicated than it looks. The three boxes for user input were coded to format the data automatically to match the field being entered, such as monetary values or percentages. This was done using a TextWatcher class that was written to fit our needs, and manipulated the data that was given. It would clean the string of characters like dollar signs, percent signs, commas, and decimals; convert it to a double or integer depending on the field that was being changed; format it for currency or percentage; and output to the interface. In addition to being able to enter values by keyboard, alternative, easier ways for user input were also implemented. One of the alternatives implemented was allowing the use of drop-down menus—known in Android Studio as Spinners—to change the number of people paying or the tip percentage quickly. Additionally, my partner was learning how to implement the OCR library so it could work alongside the user interface. I worked with her to figure out a way to parse the data read by the OCR to the interface properly. Lastly, instead of including and “equals” or “calculate” button, our design called for the tip calculator to calculate everything in real-time. After a lot of struggling, this was done by allowing our TextWatcher to access carefully selected public variables and methods in the main activity. By allowing the TextWatcher access this information, it could change the outputs shown on the interface while it formats the data entered by the user.
