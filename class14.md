# CSS 2D Transforms?
- CSS transforms allow you to move, rotate, scale, and skew elements.
The translate() Method
Translate

- The translate() method moves an element from its current position (according to the parameters given for the X-axis and the Y-axis).

The following example moves the <div> element 50 pixels to the right, and 100 pixels down from its current position.
# what is rotate ?
- The rotate() Method
Rotate
The rotate() method rotates an element clockwise or counter-clockwise according to a given degree.

# what is css transition?
- CSS transitions allows you to change property values smoothly, over a given duration.

# How to Use CSS Transitions?
- To create a transition effect, you must specify two things:

the CSS property you want to add an effect to
the duration of the effect
Note: If the duration part is not specified, the transition will have no effect, because the default value is 0.

# Specify the Speed Curve of the Transition
The transition-timing-function property specifies the speed curve of the transition effect.

 # what The transition-timing-function property can have the following values?

ease - specifies a transition effect with a slow start, then fast, then end slowly (this is default)
- linear - specifies a transition effect with the same speed from start to end
- ease-in - specifies a transition effect with a slow start
- ease-out - specifies a transition effect with a slow end
- ease-in-out - specifies a transition effect with a slow start and end
- cubic-bezier(n,n,n,n) - lets you define your own values in a cubic-bezier function

![ html and css](https://daqxzxzy8xq3u.cloudfront.net/wp-content/uploads/2019/07/15110438/css-transition-except-one-code-1024x739.png)]

#  what the CSS Animations
- CSS allows animation of HTML elements without using JavaScript or Flash!.

An animation lets an element gradually change from one style to another.

You can change as many CSS properties you want, as many times as you want.

To use CSS animation, you must first specify some keyframes for the animation.

Keyframes hold what styles the element will have at certain times.

#  what is the The @keyframes Rule?
When you specify CSS styles inside the @keyframes rule, the animation will gradually change from the current style to the new style at certain times.

To get an animation to work, you must bind the animation to an element.


# note:
- Note: The animation-duration property defines how long an animation should take to complete. If the animation-duration property is not specified, no animation will occur, because the default value is 0s (0 seconds). 

In the example above we have specified when the style will change by using the keywords "from" and "to" (which represents 0% (start) and 100% (complete)).

# Delay an Animation: 
- The animation-delay property specifies a delay for the start of an animation.

![ html and css](https://res.cloudinary.com/practicaldev/image/fetch/s--QONRcvJ6--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://thepracticaldev.s3.amazonaws.com/i/sn6p4yhoefrt1d3hmg72.jpg)]









