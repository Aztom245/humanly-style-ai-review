# Admin Login First Secure Fix

This version fixes the admin UX/security flow:

- The admin editor cannot appear before PIN login.
- The private owner page always shows the PIN login first.
- Even if an old saved admin token exists in the browser, the dashboard stays hidden until the PIN is entered again.
- After the correct PIN is entered, the admin dashboard opens normally.

Upload to GitHub:
- index.html
- README.md
- .nojekyll

No Apps Script deploy is needed for this fix.
