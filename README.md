[This is the link to the lesson](https://www.codecademy.com/courses/learn-css-variables-and-functions/lessons/learn-css-functions/exercises/css-transform-functions)

# CSS FUNCTIONS

## Transform Functions

> We can transform any HTML element using the transform property combined with CSS functions that scale, rotate, and even distort. These functions apply both 2D and 3D transformations to elements.

> The scale() function resizes an element, both horizontally and vertically, on a 2D plane. It can take either one or two parameters. If only one argument is given, scale(2) for instance, then the element will grow proportionally on both the x and y-axis. When two arguments are provided, the first argument scales along the x-axis, and the second scales along the y-axis. If you only want to scale an element on one of the two axes, either the scaleX() or the scaleY() function can be used.

> The rotate() function can be used for the transform property to rotate an element around a fixed point on a given 2D plane. The function accepts a single argument for the angle, which must be in degrees specified with the deg unit. Any positive angle means clockwise rotation, and a negative angle means counter-clockwise rotation. It is important to note that the origin of rotation defaults to the center of the element being rotated. For example, using rotate(180deg) as the value of transform property would rotate an element at its center, 180 degrees clockwise.

> Lastly, the translate() function moves an element from its initial position to another position on the page specified as the function’s arguments. The function can accept either one or two arguments—if one argument is provided, then the function will translate the element along the only x-axis by the specified amount. If two arguments are given, the element translates along the x-axis by the amount specified by the first argument and along the y-axis by the amount specified as the second argument.

```js
.shifted {
  transform: translate(0px, 100px);
}
```

> In the code example above, we wanted to shift the shifted element down the screen by 100px, so we used the transform property and set the translate() function as its value. The function’s x-axis argument was then set to be 0px and the y-axis to be 100px.

## Instructions

1. Let’s see how the card’s background image will look with another layer of interactivity.

Back in the .card:hover .bg-image selector ruleset, add a transform property below the filter property. Set the value of the transform property to be the scale() function. For the function’s argument put a value of 1.4.

Checkpoint 2 Passed

Hint
Remember that the scale() function can either scale an element up or down depending on the argument value.

2. Let’s add a bit of interaction to the card’s title! Below the .header-modifier selector rules, create an empty ruleset for the .header-modifier:hover selector.

Checkpoint 3 Passed

Hint
Make sure to add the ruleset below the .header-modifier selector rules.

3. Inside of the newly created ruleset, add a transform property. Set the value of the property to be the rotate() function with an argument of 5deg.

Now hover the cursor over the word “Argentina” to see it rotate!

Checkpoint 4 Passed

Hint
Remember to put the deg after the number in the rotate() function’s argument.

4. Finally, lets translate the mail info text at the top of the postcard. Inside the .location-details rules add a transform property with a value of the translate() function. For the function’s arguments translate the element 60% on the x-axis and 50% on the y-axis.

Don’t forget to separate the arguments with commas.

Checkpoint 5 Passed

Hint
Remember that a positive translation value on both the x-axis and y-axis will move the element down the screen and to the right.


memory jog
/c/Users/glads/Documents/PROJECTS_AT_CODECADEMY/CSS-FUNCTIONS-Transform-Functions










