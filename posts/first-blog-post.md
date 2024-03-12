---
title: First Post W1!
published_at: 2024-03-06
snippet: This is my first entry to the world of creative coding!
disable_html_sanitization: true
---

![hi hi hi](/240306_first_post/glass.png)
Hello, world!

# W1_Attempt to create Grids
## Nested Loop - For
<iframe src="https://editor.p5js.org/GemTran/full/EkDrokbRI" width="100%" height = "242px"></iframe>

I tried to many ways to create the grids based on the given code.
![pic1](/240306_first_post/CrossLines.png)
I tried to duplicate the for loop code for the vertical lines but it only ran a single vertical line.
I search many videos on how to make them and one of which was called Nested Loop.
And based on the video, it is said that nested loop can generate codes on both x and y axis of the canvas at the very same time
So I thought it might be suitable for this work. 
I created another for loop inside another for loop. I created a new variable called j for the vertical line loop and replaced it into the height value of the square operation.
![pic2](/240306_first_post/Grids.png)
However, I couldn't use the original code to initialize this loop so I had to make some changes in the values of the square.
![pic3](/240306_first_post/ColoredGrids.png)

# W1_Respond to RR's Work

## Work: Almost Calm
<iframe src="https://editor.p5js.org/GemTran/full/VGevLiGLl" width="100%" height = "242px"></iframe>

It was so hard!
At first, I created a Circle shape.
![pic4](/240306_first_post/AddShape.png)
Then finding the similar colors like in the website.
![pic5](/240306_first_post/CreateCircle.png)
I was able to do the gradient using a drawingContext to create a the gradient shape.
![pic6](/240306_first_post/TryGradient.png)
![pic7](/240306_first_post/TryGradientinBg.png)
![pic8](/240306_first_post/GradientBg.png)
![pic9](/240306_first_post/GradientBg-2.png)
Based on the Website, the background and the circle share the same gradient color but they are in opposite direction.
![pic10](/240306_first_post/Combined.png)
So I made two different gradient operation for the background and the circle using createLinearGradient()
When I tried doing the rotation, it did not work. Although I used rectMode(CENTER) to align its center point, it seemed that because drawing Context created different kind of shapes than the normal rectangle or circle shape so maybe it didn't apply to this.
![pic11](/240306_first_post/RotateWrong.png)

**Update!**
I managed to rotate the circle correctly. By assigning the coordinates of the center point, I then then move the center point of the circle to the new coordinates assigned. After that, I changed the center values in ellipse shape function to (0,0).
![pic12](/240306_first_post/RotateCircle.png)
**harddd**
_sad_