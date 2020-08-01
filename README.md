# Carousel-javascript

Create a carousel with JavaScript, HTML and CSS.

**The carousel is a slideshow for cycling through a series of content, built with CSS transforms and JavaScript. It works with a series of images, text, or custom markup. It also includes support for previous/next controls and indicators.**

![Image of Arousel](https://reactjsexample.com/content/images/2018/05/react-alice-carousel.gif)

The index.html page contains all necessary elements-container,carousel,left button,right button,slide , dot in the navigation bar and linked to the carousel-style.css file which is the stylesheet. The functions required to do the image sliding and navigating are wriiten in the slide-succession.js file.


##### The css file has elements needed for building the carousel which are:

carousel , carousel-container, container, slide,slide img, button(btn), btn img, left btn,right btn,navigation(nav), nav dot, active and hide classes.

##### The slide succession.js file has the following operations:

1)Select Carousel,next Button ,previous Button ,navigation(nav), dots, slides inside the kernel by using document.querySelector function for each entity and 
use children class to get all the dots and slides.

2)Position The Slides Horizontally,on Right Button Click, We Move(Translatex) The Carousel To The Left,on Left Button Click, We Move(Translatex) The Carousel To The Right and on the Dot Click.

3)The functions for carrying out this operations are Move to dot,move to slide, toggle active class, hide button,ind the index of an item, inside an array of items for finding out the index of active dot in dots array and target slide index from the array of slides.

## References:

[allen-kim medium article](https://medium.com/allenhwkim/how-to-build-a-carousel-in-pure-javascript-98d758a18811),[Slideshow by W3-schools](https://www.w3schools.com/howto/howto_js_slideshow.asp)

## Support 

If you like this repo and find it useful, please consider (★) starring it (on top right of the page) so that it can reach a broader audience.
