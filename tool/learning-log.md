# Tool Learning Log

## Tool: **jQuery**

---

### 03/09/25:
* Jquery has to be typed inside the script, and has to be linked to jquery.
* As of 03/01/25, <script src="https://code.jquery.com/jquery-3.7.1.min.js" integrity="sha256-/JqT3SQfawRcv/BIHPThkBvs0OEvtFFmqPF/lYI/Cxo=" crossorigin="anonymous"></script> this is the script to link jquery to workspace.
* Jquery in a way is simplified Java
* To write out Jquery, you’d write
$(“”)._____(function() {
        ___(“”);
});
* jQuery tutorial in 12 videos Tutorial for Jquery

### 03/17/25:
* An event in jQuery is when a user goes to a website and does something, and then after doing it, something else happens in the website.
* Connect id from html to your script.
* There are many types of event triggers, like .hover, .click, .dblclick, .mouseout, etc.

### 03/24/25:
* It's possible to make elements appear and disappear using jQuery
* Hide and Show, Fade are the two ways to make elements appear and disappear
* If you want jQuery to show at the bottom, wither put it on the bottom or if at the top use $(document).ready(function() {});
* If you want to target a specific img using jQuery, put it in $("#___")
* .toggle can be used to do both show and hide
* You can change the speed of how fast or slow things happen

### 04/07/25:
* When making a jQuery function using to effect names you have to make sure you capitalize the first letter of the second one(example .fadeIn)
* Speed and call makes the jQuery function run faster or slower

### 04/08/25
* .fadeToggle makes the function fade in and out, as oppose to one or the other
* 1000=1 second
* You can use .slideUp to make things slide from bottom to top
* .slideDown makes things slide from bottom to top
* Basically anything with Toggle at the end of it does both up and down actions
* Use .animate to start an animation
* When animating, you have to use curly brackets, and target the css to be changed
* Example is
$(document).ready(function(){
$(".blablabla").hover(function(){
        $(".blablabla").animate({
               width: '400px'
                height: '349px'
        });

});
});
### 04/11/25
* We can use pluses or minuses to keep increasing or decreasing the animation that you use. 
<!--
Video 5 minute 9:36
>
<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
