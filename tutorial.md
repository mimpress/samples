!SLIDE x=0 y= class=slide

> Mimpress support MultiMarkdown text format.
> 
> You can write presentation with Markdown and HTML together.




!SLIDE class=slide x=0 y=1000

> Markdown allows you to write using an easy-to-read, easy-to-write plain text format.




!SLIDE x=1000 y=-1500

Each step of the presentation should start with text "!SLIDE" and some attributes.

In the example below we only specify x and y position. This means that **the center** of the element (yes, the center)
will be positioned in point x -1000px and y -1500px of the presentation **canvas**.

It will not be rotated or scaled.




!SLIDE scale=4 x=3000 y=2000 z=3000

This is an example of step element being **scaled**.

Again, we use a **scale** attribute, so it means that this
element will be 4 times larger than the others.

From presentation and transitions point of view it means, that it will have to be scaled
down (4 times) to make it back to it's correct size.



!SLIDE rotate=90 x=1000 y=0

This element introduces rotation.

Notation shouldn't be a surprise. We use `rotate=90` attribute, meaning that this
element should be rotated by 90 degrees clockwise.




!SLIDE x=850 y=3000 z=-3000

And now it gets really exiting! We move into third dimension!
        
Along with `x` and `y` attribute, you can define the position on third (Z) axis, with
`z`. 

In the example below we use `z=-3000` meaning that element should be
positioned far away from us (by 3000px).




!SLIDE class=ing x=3500 y=2100 rotate=180

In the <b class="positioning">demo</b> that some <b class="rotating">words</b> of this text are being <b class="scaling">animated</b>.

It's a very basic CSS transition that is applied to the elements when this step element is
reached.




!SLIDE id=its-in-3d x=6200 y=4300 z=-100 rotate-x=-40 rotate-y=10 scale=2

You can not only position element in 3D, but also rotate it around any axis.
So this one here will get rotated by -40 degrees (40 degrees anticlockwise) around X axis and
10 degrees (clockwise) around Y axis.

You can of course rotate it around Z axis with `rotate-z` - it has exactly the same effect
as `rotate` (these two are basically aliases).




!SLIDE x=3500 y=3850 rotate=270
        
A summary of all the possible attributes used to position presentation steps:

* x, y, z;
* rotate-x, rotate-y, rotate-z, rotate -- rotate and rotate-z are exactly the same;
* scale

