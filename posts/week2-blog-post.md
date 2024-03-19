---
title: Week 2 Homework!
published_at: 2024-03-19
snippet: This is homework of Week 2!
disable_html_sanitization: true
---

Hi, hi, hi, another week drowning in coding!

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
# W2_Respond to RR's Work

## Work: Homage To The
<div>
    align: center;
    <iframe src="https://editor.p5js.org/GemTran/full/mJz533Gah" width="100%" height = "442px"></iframe>
</div>
I chose this work because I wanted to exercise on what we learned this week, which was array.

At first, I analysed the work on how it operates, the shapes, the size, the numbers, the flow of the animation. I also tried doing some manual calculations to make it logical within the array.

![process6](/week2/sketch.JPG)

And many more trials on the maths so I could define the conditionals for the array.

![process7](/week2/sketch2.JPG)

I declared an array called "squares" and initialised it in setup() function with the properties of size, colour, opacity.

Then created a loop in draw() function. 

![process8](/week2/Loop.png)

In HomageToThe website, as the square gets smaller, it slowly disappears and new square is being added.
Therfore, I made a conditonal method that when the size of the square is smaller than 100, which is the size of the last square in the array, it will be remove from the array and a new square will be added into the array.

However, I met difficulties in the colours and alpha value adjustments. I could not apply exactly how I did the size with these two values so I had a hard time not knowing how to calculate or control these properties.

![process9](/week2/error.png)

In the end, I think I understand how the array works better and how to create a repeated loop at basic level.
