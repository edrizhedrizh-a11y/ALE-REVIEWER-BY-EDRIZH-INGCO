# ALE Reviewer Mock Exam System

Upload instructions:
1. Extract this ZIP.
2. Upload/replace the root `index.html`.
3. Upload the whole `mock-exam/` folder to the repo root.
4. Do not modify existing subject reviewer folders.
5. Commit and hard refresh GitHub Pages.

Created structure:
mock-exam/
  index.html
mock-exam/exam-1/
  index.html
mock-exam/exam-2/
  index.html
mock-exam/exam-3/
  index.html
mock-exam/full-ale/
  index.html

Root dashboard:
- Adds one Mock Exam card pointing to ./mock-exam/
- Keeps flashcard subjects on the main dashboard.

Mock Exam notes:
- No answer reveal before submit.
- No explanation or key memory before submit.
- Randomizes questions and choices.
- Saves exam history in localStorage.
- Skips missing subject sources and shows a warning.
