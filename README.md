# Marking Homework Helper

A page for a private writing tutor. The tutor pastes a child's homework, picks Age 5 or Age 10, and gets a suggested score out of 10.0 with feedback to check, edit and approve.

- `index.html` holds the whole page: the HTML, the CSS and the JavaScript.
- The page is hosted on claude.ai and asks Claude to do the marking, so it only marks homework when it is opened there.
- Nothing is saved. Results are gone when the pop-up or the page is closed.

## Scoring

Start at 10.0. Take off 0.5 per spelling mistake, 0.5 per grammar mistake (punctuation and capital letters count as grammar) and 1.0 per logic mistake. A repeated mistake counts once. The lowest score is 0.0.
