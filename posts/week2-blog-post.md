---
title: First Post W2!
published_at: 2024-03-19
snippet: This is homework of Week 2!
disable_html_sanitization: true
---

![hi hi hi](/240306_first_post/glass.png)
Hello, world!

# W2_Attempt to use Class
## Class and Array

<iframe id="P1" src="https://editor.p5js.org/GemTran/full/atlifwKPJ" width="100%" height = "442px"></iframe>

<script type="module">
    constant iframe = document.getElementById ('P1')
    iframe.width = iframe.parentNode.scrollWidth
    iframe.height = iframe.parentNode.scrollWidth + 42
</script>
Before start working on it, I watched many video tutorials about Class method and viewed many examples of it. 

But when it came to the falling falling file, it was harder and the code was complicated with many shortcuts. 

So I thought I must at least try to how the codes work and its functions in this file. After 2 days, when I could understand its logic briefly, I started doing the reorganisation.

![process1](/week2/class_process2.JPG)

Firstly, I need to define all the properties of the faller object and methods related to it. 
![process2](/week2/class_process.JPG)

Then I added these properties in the constructor of Faller class.
I declared and assigned "faller" object to Faller class to construct new object in Set Up function. Afterthat, add to the "Fallers" array "faller" properties. 

![process3](/week2/class_sketch.png)

After many trials with errors, I managed to move on from this step.

All the methods, functions related to faller object were then reidentified by adding "faller." before them so it can recognise them.

![process4](/week2/class_final.png)

Then I called "rand.col", "rand_curve", "find_point" in the Faller Class and assigned local variables to the parameters of "find_point" so it can take values from the three arguments being called in the Draw function.

![process5](/week2/class_final2.png)

Finally, I adjusted other elements and tried to make it run.

I must say in order to come this point, I actually tried manually, added and removed stuff randomly until the errors were not shown anymore.

--
--
# W1_Respond to RR's Work

## Work: Almost Calm
<div>
    align: center;
    <iframe src="https://editor.p5js.org/GemTran/full/VGevLiGLl" width="100%" height = "442px"></iframe>
</div>
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

_sad_

**Update!**
I managed to rotate the circle correctly. By assigning the coordinates of the center point, I then then move the center point of the circle to the new coordinates assigned. After that, I changed the center values in ellipse shape function to (0,0).

![pic12](/240306_first_post/RotateCircle.png)

After I learned about lerpColor in class, I found it might be easier to use lerpColor instead of drawingContext. But then, I figured it only works for lines and it would be hard to rotate it, so I stick with my previous method. Additionally, I changed the shape of the outer gradient from rectangle to circle so the rotation can work better without seeing its edges.

**Update: Fri 15 March**
One problem I had with the rotation is that two circles will rotate at the same time because they are in the same draw function. My first solution was using Class because I just learned about it after the lecture. My approach was that separate these 2 circles to two class and create for each of that its own rotation within its class. However, it was too complicated. 

![pic13](/240306_first_post/Rotating using Class.png)

Then I found out about a video from _The Coding Train_ talking about Pop() and Push() function. Basically, I understand that Push() saves the current drawing setting below it and Pop() will mark the area of that and reset these settings. So after Pop() function, the setting will reset without losing the current transformation above. 

And, I tried applying it to my work which meaned I put the transformation and the setting of the bigger circle in push and pop function to create an opposite rotation for the smaller circle by using -angle.

![pic14](/240306_first_post/RotationFull.png)

Yayy, but I still had the mouse interaction that I have not yet done but I will come back to it when I have studied more about it.

