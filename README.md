# 🕵️ Fact Check Detective

A noir-style investigative puzzle game about spotting misinformation. Play as a newsroom detective who must vet viral stories before the morning edition goes to print.

**Theme:** DISCOVER / Digital Safety

## How to play
1. Open `fact-check-detective.html` in any modern browser (no install, no internet needed apart from an optional font).
2. Each case file shows a viral post. Use the 4 detective tools: source, date, image and claim checks.
3. Stamp your verdict: **Verified**, **Fake** or **Clickbait**, before the 45-second deadline.
4. Score points for correct calls, speed, streaks and unused tools. Wrong calls cost points.
5. Finish 8 cases to earn a rank, from Rookie Intern to Chief Inspector.

## Real-world issue
Misinformation, deepfakes, phishing forwards and clickbait spread fast and harm public health, safety and trust. The game teaches players the S.I.F.T. method (Stop, Investigate, Find better coverage, Trace claims) through short lessons after every case.

## Tech
- Plain HTML, CSS and JavaScript in a single file
- No frameworks or dependencies
- Best score saved in the browser's local storage

## Add your own cases
Edit the `CASES` array at the top of the script. Each case has an emoji, a source, a headline, a type (`real`, `fake` or `click`), four clues and a lesson.
