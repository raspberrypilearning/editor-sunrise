<h2 class="c-project-heading--task">Animating the sunrise</h2>

--- task ---

To animate your sunrise, you need to define how the sun moves and how long it takes to rise.

--- /task ---

To do this you define a list of **key frames**.

+ First, you need to use `@keyframes` to create a new animation called sunrise. 

    Add this CSS code to the end of your `style.css` file:

  This tells the sun to spend 10 seconds animating a sunrise.

<div class="c-project-code">
--- code ---
---
filename: style.css
language: css
line_numbers: true
line_number_start:
line_highlights:
---
#sun {
  position: absolute;
  left: 0;
  top: 120%;
  width: 100px;
  height: 100px;
  animation: sunrise 10s infinite;
}
@keyframes sunrise {
    0%
    100%
}

--- /code ---
</div>



timp infinate

tIP

 Each key frame defines the CSS properties of an element at a particular point in an animation. 

TIP
    This code tells the sun where to position itself at the start (`0%`) and the end (`100%`) of the animation.

    Because the sun is inside the sky `div`, the `top` and `left` positions you give are within to the sky, with `top: 100%` being the bottom of the sky, and not the bottom of the webpage.