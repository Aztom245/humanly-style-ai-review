# Owner Security Final Update

Fixes:
- Owner editor cannot appear before PIN login.
- Admin/owner URL clears saved admin token immediately.
- Editor is locked by default and only unlocks after correct PIN.
- Old auto-open admin functions are disabled.
- Change PIN now requires:
  1. Current PIN
  2. New PIN
  3. Confirm new PIN
- PIN change shows processing messages.
- Eye button shows/hides PIN fields.

Upload to GitHub:
- index.html
- README.md
- .nojekyll

Apps Script:
Replace Code.gs and deploy a new version because adminChangePin now validates the current PIN.
