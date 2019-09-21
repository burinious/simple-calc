# simple-calc
Instructions
Stage 1 --- Build the HTML
You have been provided with some HTML and CSS to guide you
-- Within the body element, create a div and give it a class = "main"
-- Within the main div, create an input with a class of textview and placeholder of 0
-- Create a table as a sibling to the input element
-- The table should contain 4 rows and each row should have 4 columns each containing a
button
-- Add another col to the table with 2 rows each containing a button
-- The 1st button should have a value of clean and text of C
-- The 2nd button should have a value of back and text should be an html code to display a
left pointing arrow
-- The 3rd button should have a value of / and text should be an html code to display a
division symbol-- The 4th button should have a value of * and text should be an html code to display a
multiplication symbol
-- The 5th button should have a value of 1 and text of 1
-- The 6th button should have a value of 2 and text of 2
-- Take a close look at the mock design of the calculator and figure out what to do to the
other buttons
-- Finally, the column containing the equals button should have an attribute of rowspan="2"
and the col containing the 0 button should have an attribute of colspan="2"
Stage 2 --- Lets make the calculator look good
-- Give the buttons a width 50px, height 50px, size of font should be 25px, margin 2px, text
color white,
the color of the background should be rgb(68, 95, 247), it should have a thin border with
radius of 5px,
the cursor should be a pointer,
and the button should change background to rgb(68, 140, 247) when the mouse is placed
over it
-- Format the textview to have a width of 207px, margin of 4px, size of font should be 25px,
text should be aligned to display from the right of the screen, it should have a thin border
with a radius of 5px
and the background should have a color of rgb(236, 231, 231)
-- Finally, the button within the col having the rowspan attribute should be given a height of
106px,
and the button within the col having the colspan attribute should be given a width of
106px
Now your app should have the expected UI
Stage 3 --- The calculator now looks good but does not function, let's make it function by
adding some JavaScript
Note: Use ES6 strictly for this project as it will help you get acquainted to it.
Use const and let appropriately for variables and Arrow functions
-- Within the script tag, create a function called "insert"; it should take a de-structured
"target" as a parameter;this will handle the insertion of the button values to the screen
-- Create another function called "equal"; this will evaluate the inserted inputs and display
the answer
-- Create another function called "clean"; it will clear the screen
-- Create another function called "back"; it will erase the content on the screen one by one
from the right
-- Lastly, create a function called "getCalculation"; this will handle all the events of the
calculator.
Now let's get to action;
-- Above the "insert" function, declare a variable called "view" and assign the textview to it.
It now represents the textview
-- Back to the "insert" function, it should concatenate the value of the target to the value on
the view and focus the view
-- The "equal" function should check if the view has a value, if it does, the view value should
be evaluated and assign the result to the view value.
-- The "clean" function should clear the value of the view
-- The "back" function should delete the last character of the value of the view
-- Within the "getCalculation" function, add a click eventListener to the buttons
and call the appropriate function in the eventListener
-- Finally, call the "getCalculation" function within the "startApp" function.
Congratulations!!! Your app should be fully functional by now.
