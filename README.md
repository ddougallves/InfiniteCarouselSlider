# Infinit Carousel slider


This is an infinite Carousel slider in javascript and css. It is lightweight and flexible. To see it working before downloading [click here](https://gitprojects.w3spaces.com/carousel/).

# Features

* Written in pure javaScript
* Flexible and extensible
* Multiple slides
* Autoplay
* Slide indicators
* Next/prev buttons

# How to add slides

To add more slides to the carousel, go to **index.html** find the following block:

~~~
<div class="carousel-inner">
    <div style="background-color: orange;" class="carousel-item"><h1>First slide</h1></div>
    <div style="background-color: greenyellow;"  class="carousel-item"><h1>Second slide</h1></div>
    <div style="background-color: rgb(37, 150, 255);" class="carousel-item"><h1>Third slide</h1></div>
    <div style="background-color: rgb(192, 192, 192);" class="carousel-item"><h1>Fourth slide</h1></div>
</div>
~~~

Now you just need to add the following code to the **div** containing the **carousel-inner** class as many times as you need to add more slides:

~~~
<div class="carousel-inner">
    <div class="carousel-item"><h1>Add your content slide here</h1></div>
</div>
~~~

# Changing the timing interval

If you wanna change the timing interval, you need to go to **script.js** e find that line:

~~~
let interval = 2000;
~~~

Here you just change the value of the variable **interval** to the value you want. Just remember to set the value to milliseconds.




