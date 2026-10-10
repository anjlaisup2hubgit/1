# Marking Homework Helper

A page for a private writing tutor. The tutor pastes a child's homework, picks Age 5 or Age 10, and gets a suggested score out of 10.0 with feedback to check, edit and approve.

## Pasting homework

Several responses can be pasted in one go. Put the student's letter or name first, then the writing:

```
J

My favourite animal is an axolotl.
```

`J: My favourite animal is an axolotl.` works too. A new response starts at each letter or name and runs until the next one. If the pasted text has no letters or names, each paragraph is a response and they are named A, B, C in order.

Each response gets its own view in the pop-up, titled `J: Age 10`. The arrows in the pop-up header move between them.

- `index.html` holds the whole page: the HTML, the CSS and the JavaScript.
- The page is hosted on claude.ai and asks Claude to do the marking, so it only marks homework when it is opened there.
- Nothing is saved. While the page stays open, the same writing keeps the same score and gets newly worded feedback each time. Everything is gone when the page is closed.

## Scoring

Start at 10.0. Take off 0.5 per spelling mistake, 0.5 per grammar mistake (punctuation and capital letters count as grammar) and 1.0 per logic mistake. A repeated mistake counts once. The lowest score is 0.0.
