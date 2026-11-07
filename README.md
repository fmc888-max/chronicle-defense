# Chronicle Defense

A tower defense game for AP World History: Modern practice. Every tower is a real development from the course. Players earn gold by answering exam-style questions.

**Play:** https://fmc888-max.github.io/chronicle-defense/ (after GitHub Pages is switched on)

## Levels

| Level | Unit | Status |
| --- | --- | --- |
| The Silk Roads, c. 1320 | 2 · Networks of Exchange | Playable |
| Gunpowder empires | 3 · Land-Based Empires | Planned |

## How it works

- One source-based multiple-choice question before each wave. Short-answer questions before waves 5 and 10.
- Missed questions come back later (spaced repetition).
- Progress saves in the browser (localStorage). The Progress screen shows accuracy by skill and topic, plus a save code for moving progress to another computer.
- Optional: a parent can add an Anthropic API key under Settings so Claude marks the short answers. The key stays in that browser only.

The questions are written in AP format for practice. They are not official College Board questions.

## Files

- `index.html` is the whole game: HTML, CSS and JavaScript in one file, with no build step.
