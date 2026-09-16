---
layout: project
type: project
image: img/fret-notes.png
title: "Fret Notes"
date: 2026-09-16
published: true
labels:
  - TypeScript
  - HTML
  - CSS
  - GitHub Pages
summary: "A guitar practice tracker I designed and built with ChatGPT assistance to organize practice sessions, set goals, and track progress."
---

<img class="img-fluid" src="../img/fret-notes.png" alt="Fret Notes guitar practice tracker showing the session form and practice progress">

Fret Notes is a guitar practice tracker that connects my interest in playing guitar with software development. I wanted a way to keep track of what I practiced instead of just remembering how long I played. The app lets me log practice time, write notes, and organize sessions into songs, scales, technique and accuracy, fretboard and theory knowledge, or miscellaneous practice.

I developed this project with ChatGPT's help generating and updating the code. My role focused on deciding what the app should do, trying the interface, and requesting changes that would make it more useful for my own practice. I proposed the practice categories, color-coded progress levels, searchable history, weekly goals, practice streaks, and weekly recap. These additions made it easier to see both what I was learning and how consistently I was practicing.

<img class="img-fluid" src="../img/fret-notes-weekly.png" alt="Fret Notes weekly goals, practice streak, and weekly recap">

The app uses TypeScript for its logic, HTML for its structure, and CSS for its appearance. The TypeScript source is converted into JavaScript so it can run in a browser. Practice sessions and goals are saved using localStorage, so they remain available after refreshing the page on the same browser. The weekly recap groups practice by category and activity, while the streak counts consecutive practice days. I published the app using GitHub Pages.

One takeaway from this project was how much a small app can change through feedback. The first version was a simple practice log, but each change helped it fit the way I wanted to use it. It also gave me a practical example of how typed objects, arrays, forms, and browser storage work together in an application.

[Try Fret Notes](https://rockymacasio.github.io/fret-notes/) | [View the source code](https://github.com/rockymacasio/fret-notes)
