<h2 align="center"> Fake </h2>

![Screen Shot 2022-11-21 at 3 41 37 PM](https://user-images.githubusercontent.com/91632194/203154411-373d6c08-afc3-433b-8341-409c522e963e.png)

![Screen Shot 2022-11-21 at 3 41 41 PM](https://user-images.githubusercontent.com/91632194/203154419-f8152399-fbeb-482b-9a62-2fe3454bfd23.png)

![Screen Shot 2022-11-21 at 3 41 45 PM](https://user-images.githubusercontent.com/91632194/203154430-6a6b6f93-f68d-4cf8-8248-483a622c0af3.png)

![Screen Shot 2022-11-21 at 3 41 51 PM](https://user-images.githubusercontent.com/91632194/203154438-a453744e-9b25-4ba7-9aab-f84d4e96ee72.png)

## Description
A website for a company called Fake. I made this mostly as an experiment with animations (the waves on the hero and about 
sections, and the floating buttons on those sections). Completely unbiased and relevant information: CSS animations are the absolute worst. As cool as they can be, they are taxing on the device and browser.

## Improve Performance on CSS Animations
If you must use CSS animations, trick your device. Add 'transform: translate3d(0, 0, 0)', 'transform: translateZ(0)' or 'transform: rotateZ(360deg)'. This will cut down CPU usage and take advantage of your GPU. I highly recommend the last option, should animations be absolutely crucial to your site. 

If none of the tricks here work, use a gif instead. It will perform better, and that's really the entire goal.   

## View
[Live Demo](https://knlrvr.github.io/fake)

## Built With 
- HTML
- CSS
- JavaScript (minimal, for mobile menu)
