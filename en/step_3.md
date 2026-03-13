<h2 class="c-project-heading--task">Creating the sun</h2>

--- task ---

Resize and position the sun by adding the CSS code below.

--- /task ---

--- task ---

Click on the file icon and open `style.css`.

![screenshot](images/step3a.png)

--- /task ---

<div class="c-project-code">
--- code ---
---
filename: style.css
language: css
line_numbers: true
line_number_start:24
line_highlights: 24-29
---

#sun {
  position: absolute;
  left: 0;
  height: 100px;
  top: 40px; /* Move the sun down */
}

--- /code ---
</div>

<div class="c-project-callout c-project-callout--tip">

### Tip

If you only set the `height`, the width updates automatically to keep the proportions the same.

</div>

--- task ---

**Test:** Run your project and check that the sun is smaller and has moved down the page.

--- /task ---

<div class="c-project-output">

![screenshot](images/step3b.png)

</div>
