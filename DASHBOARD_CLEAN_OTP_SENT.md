# Dashboard Clean + OTP Reset + Sent UI Update

This version adds:
- OTP reset warning when a saved form already exists.
- After new OTP verification, previous form data is cleared for a fresh request.
- Mark Sent user screen is visually different from normal submission waiting screen.
- Admin dashboard filters: Active, Unpaid, Verified, Sent, All.
- Verified payments turn green.
- Delete button hides submissions from the admin list.
- Sent submissions are not shown in Active view by default.
- Backend action adminDeleteSubmission.
- Backend action getPaymentStatusForClient foundation.

Upload to GitHub:
- index.html
- README.md
- .nojekyll

Apps Script:
Replace Code.gs and deploy a new version.
