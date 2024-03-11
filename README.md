# A Game Without Programming
This is a simple showcase project. Instead of using a real programming language with actual if-statements, it's written purely in CSS and HTML. It was written in 2017.

## Basic Strategy
The board is two sets of checkboxes, one for each player. In the html-element-tree, two sets of labels referencing each checkbox are placed after the checkboxes.

CSS is used to hide one layer and labels of checkboxes already ticked. Similarly, CSS is used to detect winning conditions and the winner. After winning, no layer is shown so no changes happen (ideally, known unfixed bugs exist), winner is displayed and the game is over. Restart by reloading browser.

## Disclaimers / Caveats
This was a quick hack because I wanted to stretch a simple concept. There are no tests, there are known bugs. All of this is my own work, but since then I have found work by another talented artist using only CSS and HTML: http://www.cssplay.co.uk/menu/tilt.html