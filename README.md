# A basic A-Frame scene

This page contains a basic scene that is created using the a-frame library https://aframe.io/

This whole scene is a single html file. HTML files are files containing webpages.

You could save the file [index.html](index.html) to your computer (e.g. by cloning this repo). Then you can open it in a browser to view it.

## Editing using a sandbox
There are many sandbox environments on the web preconfigured to edit html+javascript code. To open any github repo in [codesandbox.io](https://codesandbox.io) change the url from ```github.com/[...]``` to ```githubbox.com/[...]```. Note that any changes you do will be stored on [codesandbox.io](https://codesandbox.io) and will not be contributed back to this repository. 

Here is how it should look like in your sandbox:

<p align="center"><img src="https://user-images.githubusercontent.com/7040974/214770151-1ac1abf4-a76e-4991-a0e5-b353be9eedc7.png"
alt="Sandbox view" width="500em" /></p>

You can: 
- fork the sandbox to make changes to it
<p align="center"><img src="https://user-images.githubusercontent.com/7040974/214770251-13e2dcb3-f6e8-41ab-bfe5-514794470649.png"
alt="fork button in the sandbox environment"
width="300em" /></p>

- close the left side panel to have more room to edit

- move around the scene in the right window
<p align="center">
<img src="https://user-images.githubusercontent.com/7040974/214770405-2a0e8101-bb1a-420d-be74-62422c0b9955.png" alt="The live preview of the scene" width="500em" /> </p>

- pop out the window into a separate tab if you want more room to code and explore:
<p align="center"><img src="https://user-images.githubusercontent.com/7040974/214770573-b0d5bbf3-5a81-4b28-b3a3-96066fbf5160.png" width="500em"
/> </p>



## Basic HTML
This page is written in HTML+Javascript. Take a look at 
 a [html crash course](https://www.w3schools.com/html/html_intro.asp) if you are unfamiliar, but you can pick up the basics by experimenting and playing around. 

 The best way to play around is to create a sandbox on [codesandbox.io](https://codesandbox.io).

### Comments

Comments in html are enclosed in comment tags like this

```html
<!--
    This is a comment
-->
```
Comments are free text that is NOT interpreted by the browser in any way

### Static webpage
This webpage is static. That is why it works without a "server". All the logic and processing is done by your browser.

### A-frame and other libraries

The library a-frame, used for creating immersive graphical websites is pulled in 
is pulled in through the ```<script>``` tag in the header of this html file. The library is not stored on your computer, it is downloaded from the internet by your browser.

Documentation for a-frame is available from https://aframe.io/docs/master/introduction/

