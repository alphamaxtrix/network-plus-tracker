# Network+ Study Tracker

A self-contained study toolkit for [Professor Messer's free CompTIA N10-009 Network+ video course](https://www.professormesser.com/network-plus/n10-009/n10-009-video/n10-009-training-course/). Track which videos you've watched and quiz yourself on key topics, all in the browser.

**Live site:** https://alphamaxtrix.github.io/network-plus-tracker/
**Quiz:** https://alphamaxtrix.github.io/network-plus-tracker/quiz.html

## Pages

### `index.html` — Video Tracker
- All 87 videos from the course, organized by section and subsection
- Click a video to mark it complete — progress saves automatically in your browser
- Per-section progress bars in the sidebar
- Overall completion percentage and time watched / time remaining
- Direct links to each video on Professor Messer's site

### `quiz.html` — Practice Quiz
- 5 categories: Ports & Protocols, Subnetting & IP Addressing, Devices & OSI Model, Security & Attacks, Troubleshooting & Tools — plus a Mixed Review mode
- 10 random multiple-choice questions per round
- Tracks accuracy per category over time
- Review screen highlights missed questions and correct answers

Both pages link to each other from the top bar.

## Usage

Visit the live site above, or open `index.html` / `quiz.html` directly in a browser. Progress and quiz stats are stored locally in your browser (`localStorage`), so they're tied to whichever browser/device you use — they won't sync across devices.

To reset tracker progress, use the "Reset progress" button in the bottom right of the tracker.

## Mobile support

Both pages are responsive and usable on phones — the layout stacks vertically, touch targets are sized for tapping, and the section nav becomes a horizontal scroll strip on narrow screens.

## Tech

Plain HTML, CSS, and vanilla JavaScript. No frameworks, no build tools. Hosted for free on GitHub Pages.

## Course coverage

| Section | Topic | Videos |
|---|---|---|
| 0 | The N10-009 Exam | 1 |
| 1 | Networking Concepts | 30 |
| 2 | Network Implementation | 14 |
| 3 | Network Operations | 16 |
| 4 | Network Security | 14 |
| 5 | Network Troubleshooting | 12 |

## Credit

All course content and video links belong to [Professor Messer](https://www.professormesser.com/). This is just an unofficial personal tracker and quiz for following along with his free training videos.

