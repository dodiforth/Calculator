# Calculator
Build a calculator app with Tim Buchalka on Udemy
In this section, we're going to look at working with groups of widgets, to see how we can do things like 
constraining them to be positioned as a group, as well as setting common properties for multiple widgets at the same time.

We'll also show a slightly different approach to creating an OnClickListener, so that the same method can be used by multiple buttons.

This app is going to be a basic calculator.
It will let you enter numbers using the app's buttons, 
then performs the calculation when any of the operation keys are pressed (plus, minus, multiply and divide).

The stock Andndroid calculator builds up the calculation on the screen, and doesn't actually evaluate it until you press the equals key.
Ours is going to evaluate each sum as soon as you press the next operator, just like early calculators did.
We'll have two lines of display though, so you can see both numbers at once,
and don't have to remember the previous one like you did with those early calculators.

Also unlike the early calculators, it will show you which operation it will perform next,
so you don't loose track. Pressing equals will update the display with the result,
and can also be used to start a new calculation - by transferring the entered number up into the result,
ready to use in the next calculation.
