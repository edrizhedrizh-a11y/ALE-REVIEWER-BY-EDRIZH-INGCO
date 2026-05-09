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


v2 visual update:
- Mock Exam now shows safe question-side visuals before submit.
- Direct question images are displayed.
- If a card has only a visual query, buttons are shown for image search / Wikimedia Commons.
- Answer-side visual, explanation, key memory, and correct answer still stay hidden until submit.
- Review pages show visual references after submit.


v3 randomization/retake update:
- Default Start Exam always generates a new random question set.
- Each attempt stores selected question IDs in localStorage.
- After submit: Start New Random Exam, Retake Same Exam, Review Wrong Answers.
- Retake Same Exam reuses the exact saved question IDs from the last attempt.
- Full ALE segments also save exact question IDs and support Retake Same Segment.
- Exam 3 / Day 2 shows a Design Problem pending note.


v4 PRC layout/confidence update:
- Added PRC Split View mode for iPad/tablet/laptop/desktop.
- Added Compact Mobile mode for phones.
- Added layout toggle: Auto, PRC Split View, Compact Mobile.
- Added sticky/collapsible answer sheet with A/B/C/D bubbles.
- Added confidence marks independent from answer: Sure, Not Sure, Guess, No Idea, Clear Mark.
- Added answer sheet filters and quick review buttons.
- Added Next Matching / Previous Matching in review filter mode.
- Submit confirmation now shows answered/unanswered/confidence summary/time remaining.
- Results include performance breakdown by confidence mark.
- Day 2 / ADSP shows Design Problem pending note.


v5 Test Booklet Markup Mode:
- Added Apple Pencil / stylus annotation layer per question.
- Tools: Navigate, Pencil, Highlighter, Eraser.
- Buttons: Clear Notes for This Question, Hide/Show Notes, Undo Last Stroke, Fullscreen Question, Open Scratch Pad.
- Notes are saved as lightweight vector strokes in localStorage by examAttemptId and questionId.
- Typed scratch notes are included as a phone/keyboard fallback.
- Notes persist when leaving and returning to a question.
- Notes remain visible after submit in review mode.
- Added Clear Notes After Review option.
