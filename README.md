# Marking Homework Helper

A page for a private writing tutor. The tutor pastes a child's homework, picks Age 5 or Age 10, and gets a suggested score out of 10.0 with feedback to check, edit and approve.

## Pasting homework

Several responses can be pasted in one go, with an empty line between them. Each response may start with a letter or a name, written as `J: the writing` or as `J` on its own line above the writing. A response with no letter or name is given one in order: A, B, C.

Each response gets its own view in the pop-up, titled `J: Age 10`. The arrows in the pop-up header move between them.

- `index.html` holds the whole page: the HTML, the CSS and the JavaScript.
- The page is hosted on claude.ai and asks Claude to do the marking, so it only marks homework when it is opened there.
- Nothing is saved. While the page stays open, the same writing keeps the same score and gets newly worded feedback each time. Everything is gone when the page is closed.

## Scoring

Start at 10.0. Take off 0.5 per spelling mistake, 0.5 per grammar mistake (punctuation and capital letters count as grammar) and 1.0 per logic mistake. A repeated mistake counts once. The lowest score is 0.0.
