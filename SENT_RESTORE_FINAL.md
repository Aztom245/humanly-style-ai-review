# Sent + Restore Final Fix

Fixes:
1. Unknown action for Mark Report as Sent:
   - adminMarkReportSent added/confirmed
   - getSubmissionStatus added/confirmed
   - submitFeedback added/confirmed

2. Refresh restore:
   - Form fields save automatically
   - Uploaded files save where browser storage allows
   - Payment/session fields restore
   - Active countdown restores after refresh

3. Admin convenience:
   - Quick Mark Sent box is now at the top of the owner dashboard
   - You no longer need to scroll down to mark sent

GitHub:
Upload index.html, README.md, .nojekyll

Apps Script:
Replace Code.gs and deploy a new version because backend actions were fixed.
