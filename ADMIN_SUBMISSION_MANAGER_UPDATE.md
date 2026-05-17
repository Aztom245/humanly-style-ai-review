# Admin Submission Manager Update

This version adds:

1. Automatic submission list in admin:
   - Recent submissions appear in the owner dashboard.
   - Refresh button loads latest submissions.

2. Admin Verify Payment:
   - Use when payment succeeded but the website did not recognize it.
   - Admin can manually mark payment as verified.

3. Admin Mark Sent:
   - Admin can mark a report as sent directly from the submission card.

4. Backend actions added:
   - adminListSubmissions
   - adminVerifySubmissionPayment
   - adminMarkReportSent
   - getSubmissionStatus

Upload to GitHub:
- index.html
- README.md
- .nojekyll

Apps Script:
Replace Code.gs and deploy a new version.
