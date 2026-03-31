<h2 class="c-project-heading--task">Diagonal animation</h2>

--- task ---

Change the `sunrise` keyframes so the sun rises, pauses at the top, then sets again.

--- /task ---

--- task ---

Open `style.css` and find your `@keyframes sunrise` animation.

Update the keyframes so the sun:

- starts at the bottom of the sky
- reaches the top by `33%`
- stays at the top until `66%`
- returns to the bottom by `100%`

--- /task ---

<div class="c-project-code">
--- code ---
---
filename: style.css
language: css
line_numbers: true
line_number_start: 1
line_highlights: 2-5
---

@keyframes sunrise {
  0%   { left: 0;   top: 120%; }
  33%  { left: 20%; top: 0; }
  66%  { left: 60%; top: 0; }
  100% { left: 80%; top: 120%; }
}

--- /code ---
</div>

<div class="c-project-callout c-project-callout--tip">

### Tip

- `left` moves the sun sideways across the sky (0% is the left edge).
- `top` moves the sun up and down inside the sky (`top: 100%` is the bottom of the sky).
- Try changing the `left` values to make the sun rise at a steeper or shallower angle.

</div>

--- task ---

**Test:** Run your project and check the sun rises, pauses near the top, then sets again.

--- /task ---

<div class="c-project-output">

![screenshot](images/step5.gif)

</div>