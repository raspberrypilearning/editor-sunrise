## Introduction

In this project, you'll learn how to use CSS to create an animated sunrise.

<div class="trinket">
  <iframe src="https://trinket.io/embed/html/abcc0284a3?outputOnly=true&start=result" width="600" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
  <img src="images/sunrise-final.png">
</div>

### Additional information for club leaders

If you need to print this project, please use the [Printer friendly version](https://projects.raspberrypi.org/en/projects/sunrise/print).

--- collapse ---
---
title: Club leader notes
---

## Introduction:

In this project, children will to learn how to animate a simple scene using CSS. They will use the CSS @keyframes rule to animate various properties of images and divs.

## Online Resources

We recommend using [trinket](https://trinket.io/) to write HTML & CSS online. This project contains the following trinkets:

+ ['Sunrise' starting point](http://jumpto.cc/web-sunrise)

Children can also make use of this blank trinket [(jumpto.cc/html-blank)](http://jumpto.cc/html-blank) to write their own HTML & CSS, or alternatively they can use this template trinket [(jumpto.cc/html-template)](http://jumpto.cc/html-template).

There is also a trinket containing a sample solution to the challenges:

+ ['Sunrise' Finished](https://trinket.io/html/abcc0284a3)

## Offline Resources

This project can be [completed offline](https://rpf.io/html-offline) if preferred. You can access the project resources by clicking the 'Download Project Materials' link for this project. This link contains a 'Project Resources' folder, which includes resources that children will need to complete this project offline. Make sure that each child has access to a copy of these resources. This folder includes the following files:
 
+ template/index.html
+ template/prefix.js
+ template/style.css
+ sunrise/index.html
+ sunrise/style.css
+ sunrise/prefixfree.js
+ sunrise/boat.png
+ sunrise/cloud.png
+ sunrise/helicopter.png
+ sunrise/rainbow.png
+ sunrise/sun.png

You can also find a completed version of this project's challenges in the 'Volunteer Resources' section, which contains:

+ sunrise-finished/index.html
+ sunrise-finished/style.css
+ sunrise-finished/prefixfree.js
+ sunrise-finished/boat.png
+ sunrise-finished/sun.png
+ sunrise-finished/rainbow.png

## Learning Objectives

+ Styling and animation with CSS:
	+ Introducing `@keyframes` rule for defining steps in an animation.
	+ Reinforcing the use of properties to define the size, shape, position and colour of elements on a webpage.

This project covers elements from the following strands of the [Raspberry Pi Digital Making Curriculum](http://rpf.io/curriculum):

+ [Design basic 2D and 3D assets](https://www.raspberrypi.org/curriculum/design/creator).

## Challenges

+ "Diagonal animation" - editing animation `@keyframe` properties to use left:;
+ "Improve the sky" - add more keyframes and setting background:.
+ "More animation" - animate more images or elements using a variety of CSS properties. 

## Frequently Asked Questions

+ This project makes use of the javascript `prefixfree.js` library, to allow animation compatibility between browsers. If this library isn't used, then children using older browsers will instead need to declare an animation for their browser, for example:

```
animation: sky 10s infinite; 		  	//for all newer browsers
-webkit-animation: sky 10s infinite;  	// For Webkit browsers(Chrome, Safari...)
-moz-animation: sky 10s infinite;     	// For Mozilla browsers
-o-animation: sky 10s infinite;       	// For Opera browsers
-ms-animation: sky 10s infinite;		// For Microsoft browsers 
```

--- /collapse ---

--- collapse ---
---
title: Project materials
---

## Project resources

* [.zip file containing all project resources](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-project-resources.zip)
* [Online Trinket containing all 'Sunrise' project resources](http://jumpto.cc/web-sunrise)
* [Online Trinket template](http://jumpto.cc/trinket-template)
* [Online blank Trinket](http://jumpto.cc/trinket-blank)
* [template/index.html](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/template-index.html)
* [template/style.css](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/template-style.css)
* [intro/index.html](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/intro-index.html)
* [intro/style.css](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/intro-style.css)
* [sunrise/index.html](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-index.html)
* [sunrise/style.css](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-style.css)
* [sunrise/prefixfree.js](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-prefixfree.js)
* [sunrise/sun.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-sun.png)
* [sunrise/rainbow.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-rainbow.png)
* [sunrise/cloud.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-cloud.png)
* [sunrise/boat.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-boat.png)
* [sunrise/helicopter.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-helicopter.png)

## Club leader resources

* [.zip file containing all completed project resources](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-volunteer-resources.zip)
* [Online completed Trinket project](https://trinket.io/html/abcc0284a3)
* [sunrise-finished/index.html](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-index.html)
* [sunrise-finished/style.css](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-style.css)
* [sunrise-finished/prefixfree.js](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-prefixfree.js)
* [sunrise-finished/sun.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-sun.png)
* [sunrise-finished/boat.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-boat.png)
* [sunrise-finished/rainbow.png](https://github.com/raspberrypilearning/sunrise/raw/master/en/resources/sunrise-finished-rainbow.png)

--- /collapse ---
