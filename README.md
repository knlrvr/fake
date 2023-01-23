<h2 align="center"> Fake </h2>

![Screen Shot 2022-11-21 at 3 41 37 PM](https://user-images.githubusercontent.com/91632194/203154411-373d6c08-afc3-433b-8341-409c522e963e.png)

## Description
A website for a company called Fake. I made this mostly as an experiment with animations (the waves on the hero and about 
sections, and the floating buttons on those sections). Completely unbiased and relevant information: CSS animations are the absolute worst. As cool as they can be, they are taxing on the device and browser.

## Improve Performance on CSS Animations
If you must use CSS animations, trick your device. Add 'transform: translate3d(0, 0, 0)', 'transform: translateZ(0)' or 'transform: rotateZ(360deg)'. This will cut down CPU usage and take advantage of your GPU. I highly recommend the last option, should animations be absolutely crucial to your site. 

If none of the tricks here work, use a gif instead. It will perform better, and that's really the entire goal. 

Another note; don't take my word for any of this. This is just my experience and my suggestions based on that experience. But use a gif. 

## View
[Live Demo](https://knlrvr.github.io/fake)

## Built With 
- HTML
- CSS
- JavaScript (minimal, for mobile menu)
