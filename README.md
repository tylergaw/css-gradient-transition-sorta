## What's this all about?

Currently, it seems that it is not possible to animate a CSS gradient background image with a CSS transition. [This article](http://screenflicker.com/mike/code/more-webkit-transition-funniness) says that it is possible (at the time, only with Webkit), but I've not been able to get it to work following the instructions in the article.

This is a workaround I used that worked for my purposes, maybe it will work for you.

Instead of animating the background gradient, I animate the background color. I needed to set the colors of the gradient to be partially transparent so you can see through them to the background color.

Since I was then working with partially transparent colors, I needed to either brighten or darken the colors so that their default state matched what was originally designed. I don't have an exact formula for this, I would just eyeball it until it looked right.
