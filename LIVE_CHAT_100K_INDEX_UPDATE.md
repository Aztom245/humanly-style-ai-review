# Live Chat 100k Q&A Indexed Update

CSV rows read: 100000
Q&A records indexed: 100004
Question column: User Question
Answer column: Appropriate Answer

What changed:
- The uploaded CSV was converted into lightweight JSON chunks in /chat-data.
- The live chat detects the user's likely category and loads only those category files.
- It scores answers and returns the best answer.
- Greetings like hello/how are you are handled naturally.
- Valid email is still required.
- Chat still logs to Apps Script and Telegram.
- If no strong answer is found, it falls back to the existing Apps Script auto-reply.

Upload to GitHub:
- index.html
- README.md
- .nojekyll
- full chat-data folder

Apps Script:
Replace Code.gs and deploy a new version.
