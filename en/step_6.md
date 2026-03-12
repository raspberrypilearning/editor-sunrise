<h2 class="c-project-heading--task">Sky</h2>

--- task ---

Animate the sky so it turns dark at night while the sun rises and sets.

--- /task ---

--- task ---

Open `style.css` and find the `#sky` CSS rule.

Add an animation called `sky` so the background colour changes over time.

Then add a `@keyframes sky` animation so the sky is dark at the start and end, and light blue in the middle.

--- /task ---

<div class="c-project-code">
--- code ---
---
filename: style.css
language: css
line_numbers: true
line_number_start: 1
line_highlights: 7-20
---

#sky {
  position: absolute;
  top: 0;
  width: 100%;
  height: 50%;
  background: lightblue;
  animation: sky 10s infinite; /* Match the sun's timing so they sync */
}

@keyframes sky {
  0%   { background: black; }
  33%  { background: lightblue; }
  66%  { background: lightblue; }
  100% { background: black; }
}

--- /code ---
</div>

<div class="c-project-callout c-project-callout--tip">

### Tip

- You can experiment with colours by typing a colour name (like `blue`) and clicking it in the editor to preview.
- Try changing `lightblue` to another colour to make a different daytime sky.

</div>

--- task ---

**Test:** Run your project and check the sky changes colour over time, getting darker when the sun is “down”.

--- /task ---

<div class="c-project-output">

![screenshot](images/step6.png)

</div>