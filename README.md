# bsplinecurve

This repostory shows different techniques to draw curves and lines which are used in computer graphics.

-   [Draw Line based on middle points](#draw-line-based-on-middle-points)
-   [Draw Line based on bezier method](#draw-line-based-on-bezier-method)
-   [Draw Curves based on bezier method](#draw-curves-based-on-bezier-method)

# Draw Line based on middle points

This method does not require a lot of explanation, cause it is so straight forward technique. When we want to use this technique, we just define two points and recursively find middle points. In my case, count of iterations is 5.

![Demo middle gif](demos/demo-middle.gif)

# Draw Line based on bezier method

Another method to draw a line is find a linear function which will look like y = k \* x + b. After finding this function, you can increase the value of x and put a dote in this point.

![Demo line gif](demos/demo-line.gif)
