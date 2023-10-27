# DOM Practice Assessment

This is a practice exam to help you prepare for the DOM exam. Write your code in the `<script>` area at the bottom of `assessment.html`. 

NOTE: there are no unit tests for this exam. Check the correctness of your work by looking at the visible changes in the HTML document.


## Problem 1
When the button with an id of `btn-problem1` is clicked, set the background color of the paragraph with id `par-problem1` to blue.

## Problem 2
When the button with an id of `btn-problem2` is clicked, reload the page. 

*Hint: it's a BOM function.*

## Problem 3
Whenever the user types in the text input with an id of `input-problem3`, change the background color of the paragraph with id `par-problem3` to the whatever the user typed. For example, if the user types "red", then the paragraph's background color would change to red. 

*Hint: the event type can be any of the keyboard events, OR you can also use the "change" event type.*

## Problem 4
Whenever the user hovers over ANY `li` element with a class of `li-problem4`, the text of THAT `li` will become bold. When the user stops hovering over on that `li`, the text of THAT `li` will stop being bold. 

*Hint: use `.querySelectorAll` to get all the `li` elements and use a loop to add the event listeners to each one.*

*Hint: you can use the class `my-font-bold` to add/remove or toggle the element's font weight.*

## Problem 5
Whenever the user hovers over the image with an id of `pbjt-problem5`, change the image's `src` attribute to "images/pbjt_2.gif". When the user stops hovering over the image, change the image's `src` attribute back to "images/pbjt_1.png";

## Problem 6
Whenever the user clicks the button with an id of `btn-problem6`, create an interval that toggles EVERY SECOND the class `my-blue` for the paragraph with an id of `par-problem6`. If the button is clicked again, the interval will be removed. 

*Hint: use a global variable to store the interval id. When the button is clicked a 2nd time, if the interval id has been set, then you know you need to remove it.*

## Problem 7
When the user clicks the button with an id of `btn-problem7`, toggle the class `my-green` for all `H4` elements.