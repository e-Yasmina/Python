# Python Cheat Sheet (py.html)

A concise, printable Python 3 cheat sheet implemented as a single HTML file: [py.html](py.html).

What this file is
- A visual cheat sheet that renders a grid of cards containing short Python examples and notes.
- Data for the cards is stored in the [`cardsData`](py.html) array and rendered into the DOM element [`cardsContainer`](py.html).

Quick start
- Open [py.html](py.html) in a browser to view the cheat sheet.
- No build step required.

How to edit or add entries
- Open [py.html](py.html) and locate the [`cardsData`](py.html) array in the script.
- Each card is an object with fields: title, code, desc.

Example card (add to the cardsData array):
```python
{ title: "Example", code: 'print("Hello")', desc: "Simple print example" }