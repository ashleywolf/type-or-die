# :zombie: Type or Die

Zombies are shambling toward you with words on their heads. Type fast or get eaten.

## [Play Now](https://ashleywolf.github.io/type-or-die/) (Chrome/Edge)

## What Is This

A typing survival game where every wave gets nastier. Round 1 gives you "cat" and "dog." By round 10, you're panic-typing "pneumonoultramicroscopicsilicovolcanoconiosis" while four zombies close in. Three lives. No mercy.

## Features

- 10+ waves of escalating vocabulary that goes from kindergarten to SAT prep to medical dictionary
- Zombies color-coded by word length: green (easy), blue (medium), red (hard), purple (you're in trouble)
- Combo timer with a visual arc that rewards speed kills
- Screen shake when you nail a zombie, red flash + buzz when you mistype
- Wave transition fanfare so you can catch your breath for exactly 2 seconds
- Ambient drone soundtrack that gets more ominous each wave
- localStorage high scores that persist between sessions
- Wrong keypress penalty makes fat-fingering hurt

## How to Play

- Zombies approach from the top. Each one has a word above its head.
- Type the word to kill the zombie before it reaches you.
- Build combos by killing fast. Miss a letter and the combo breaks.
- Survive all waves, or die trying.

## Tech

- Pure vanilla JavaScript and HTML5 Canvas
- No frameworks, no dependencies, no build step
- KeyboardEvent handling with real-time input matching
- Web Audio API for ambient sound and hit/miss feedback

## Browser Support

Chrome or Edge recommended. Works in any modern browser with keyboard input.

## Part of Browser Party Games

8 single-file browser games built with MediaPipe, Transformers.js, Web Audio, and Web Speech. No servers, no build steps, no installs.

| Game | Input | Tech |
|------|-------|------|
| [Type or Die](https://ashleywolf.github.io/type-or-die/) | Keyboard | Vanilla JS |
| [Grin Sweeper](https://ashleywolf.github.io/grin-sweeper/) | Smile (webcam) | MediaPipe Face |
| [Show & Tell](https://ashleywolf.github.io/show-and-tell/) | Real objects (webcam) | Transformers.js DETR |
| [Pitch Climber](https://ashleywolf.github.io/pitch-climber/) | Voice pitch (mic) | Web Audio API |
| [Spell Caster](https://ashleywolf.github.io/spell-caster/) | Shout spells (mic) | Web Speech API |
| [Stone Face](https://ashleywolf.github.io/stone-face/) | Don't react (webcam) | MediaPipe Face |
| [Ninja Hands](https://ashleywolf.github.io/ninja-hands/) | Hand tracking (webcam) | MediaPipe Hands |
| [Duck & Cover](https://ashleywolf.github.io/duck-and-cover/) | Duck + yell (webcam+mic) | MediaPipe Pose + Web Audio |

---
Built with vanilla JS + browser ML. Each game is one HTML file. Fork it, break it, make it yours.
