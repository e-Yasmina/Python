# Python Learning Collection — Overview & Cheat Sheet

A small collection of single-file HTML resources for learning Python: basics, exercises, problem solving, game-based learning, debugging, and tests. Each HTML file is standalone and uses Prism.js for syntax highlighting.

## Contents
- `py.html` — Python Basics (cheat sheet / reference)
- `python_basics.html` — Python exercises and short lessons
- `problems.html` — Problem-solving drills and challenges
- `game-based.html` — Learning via simple games
- `debugging.html` — Debugging examples and tips
- `test.html` — Tests and interactive exercises 

## What each page provides
- Python Basics: concise examples, common idioms, types, control flow, functions, and snippets.
- Exercises: short editable exercises to practice specific topics.
- Problems: larger algorithmic tasks to build problem-solving skills.
- Game-based: fun projects (e.g., Rock-Paper-Scissors) to apply concepts.
- Debugging: buggy code samples with guided fixes and explanations.
- Test: curated exercises, multiple-choice or code-fix tasks, and revealable solutions (toggle).

## Quick start (Windows)
- Open any page in your browser. Example for the Test page:
  start "" "c:\..\...\...\Python\test.html"

## Editing & Adding Content
- Files are plain HTML; open in VS Code to edit.
- Code blocks in the pages use `<pre><code class="language-python">...</code></pre>` and many are editable (contenteditable) so learners can try changes in-place.
- To add an exercise or problem:
  - Add a new `<section class="exercise-section">...</section>` following the existing structure.
  - Include question, editable code block, a solution toggle button and a `.solution-content` div with the solution.
  - Call `Prism.highlightAll()` if you dynamically inject code snippets.

## UI / Behavior notes
- Solutions are hidden by default and revealed using `toggleSolution(id)` in the pages.
- Prism.js is used for syntax highlighting via CDN (no build step required).

## Contributing
- Edit files directly in this workspace and test them by opening in the browser.
- Keep examples short, use plain Python 3 syntax, and include expected output or comments where helpful.

Note on py.html inspiration
- The Python Basics page (`py.html`) is inspired by "quick reference" (cheat sheet) style resources. 
