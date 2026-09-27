# Mancala

A browser-based implementation of the classic Mancala board game. No installs, no dependencies — just open `index.html`.

## How to Play

1. Open `index.html` in any modern browser
2. Two players take turns on the same screen
3. Click a pit on your side to pick up and distribute its stones
4. Most stones in your store at game end wins

## Rules

- **Extra turn**: Land your last stone in your own store to go again
- **Capture**: Land your last stone in an empty pit on your side — steal all stones from the opponent's opposite pit
- **Game end**: When one player's side is empty, remaining stones move to the owner's store

## Features

- Move preview on hover (highlights landing pit, flags captures and extra turns)
- Animated stone flight with physics-based easing
- Procedural audio via Web Audio API (no audio files)
- Fully self-contained in a single HTML file

## Tech

Vanilla HTML, CSS, and JavaScript. No frameworks, no build step.
