<h2 class="c-project-heading--task">Animating the sunrise</h2>

--- task ---

Create a `sunrise` keyframe animation that makes the sun rise and then set over 10 seconds.

--- /task ---

--- task ---

Open `style.css`.

Find your `#sun` CSS rule and make sure it uses the `sunrise` animation.

Then add a `@keyframes sunrise` animation at the end of the file so the sun starts at the bottom, reaches the top halfway through, then returns to the bottom.

--- /task ---

<div class="c-project-code">
--- code ---
---
filename: style.css
language: css
line_numbers: true
line_number_start: 1
line_highlights: 7,10-14
---

#sun {
  position: absolute;
  left: 0;
  top: 120%;
  width: 100px;
  height: 100px;
  animation: sunrise 10s infinite; /* Run the sunrise animation over 10 seconds, repeating forever */
}

@keyframes sunrise {
  0%   { left: 0;   top: 120%; }
  50%  { left: 40%; top: 0; }
  100% { left: 80%; top: 120%; }
}

--- /code ---
</div>

<div class="c-project-callout c-project-callout--tip">

### Tip

- `0%` is the start of the animation and `100%` is the end.
- Each keyframe sets the sun’s position at that moment in time.
- Because the sun is inside the sky `div`, `top` and `left` are relative to the sky — `top: 100%` is the bottom of the sky, not the bottom of the webpage.

</div>

--- task ---

**Test:** Run your project and check the sun rises up to the top, then sets again, and repeats.

--- /task ---

<div class="c-project-output">

![screenshot](images/step4.png)

</div>