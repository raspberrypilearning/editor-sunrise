<h2 class="c-project-heading--task">Challenge: Diagonal animation</h2>

--- task ---



--- /task ---

+ If you want the sun to rise and then set, just add more keyframes to your animation:

   This means that the animation starts and ends with the sun at the bottom of the sky, and stays at the top from 33% until 66% of the animation.

<div class="c-project-code">
--- code ---
---
filename: style.css
language: css
line_numbers: true
line_number_start:
line_highlights:
---

@keyframes sunrise {
    0%  
    33% 
    66% 
    100%
}

look into wha the left and top are???
@keyframes sunrise {
  0%   {left:0; top:120%;}
  33%  {left:40%; top:0;}
  66%  {left:40%; top:0;}
  100%  {left:80%; top:120%;}
}
