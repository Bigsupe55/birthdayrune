# BIRTHDAYRUNE

A Deltarune-style birthday minigame, built as a gift. Play it at
https://bigsupe55.github.io/birthdayrune/

[![topics](https://img.shields.io/badge/built%20with-vanilla%20JS-f7df1e)](index.html)

## What it is

One `index.html` file, about 1,200 lines. No dependencies, no build step, no bundler,
nothing to install. Open the file and it runs.

- **Canvas rendering** with a `requestAnimationFrame` game loop
- **Web Audio API** for the music and sound effects, synthesized in-browser rather than
  shipping audio files
- **Turn-based battle system** in the style of Deltarune: FIGHT / ACT / SPARE menu
  actions, an enemy turn where you steer a soul to dodge bullet patterns, and HP that
  carries between turns

Everything lives in one file on purpose. It made the whole thing sendable as a single
link, and there is something clarifying about a game with no import graph.

## Running it locally

```bash
open index.html
```

That is the entire process. There is no server, no `npm install`, and no configuration.

## A note on the source material

This is a non-commercial fan project, made once as a gift. Deltarune and its characters
are the work of Toby Fox. No assets from the original game are used here: the visuals are
drawn to canvas and the audio is synthesized at runtime.
