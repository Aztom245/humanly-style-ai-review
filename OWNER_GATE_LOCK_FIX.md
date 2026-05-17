# Owner Gate Lock Fix

This version fixes the issue where the Owner editor opened before PIN login.

What changed:
- On owner/admin URL, saved admin token is cleared immediately.
- Admin editor/modal is hard-locked by CSS until the correct PIN is entered.
- Old auto-open admin functions are blocked on the private owner page.
- After correct PIN, the owner dashboard opens normally.
- People cannot see the editor before PIN login.

Upload to GitHub:
- index.html
- README.md
- .nojekyll

No Apps Script deploy is needed.
