# Admin Sent Status Update

This version adds:

1. Clearer, premium, easy-to-understand homepage/service copy.
2. User-facing explanation that the system is AI trained/guided by human expert knowledge.
3. Admin tool: Mark Report as Sent.
4. User waiting screen polls the backend every 30 seconds.
5. If admin marks the report as Sent while the user is still on the page, the countdown changes to “Report sent”.

GitHub upload:
- index.html
- README.md
- .nojekyll

Apps Script:
Because this version adds adminMarkReportSent and getSubmissionStatus actions, replace Code.gs and deploy a new version.
