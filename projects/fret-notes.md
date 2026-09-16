---
layout: project
type: project
image: img/fret-notes.png
title: "Fret Notes"
date: 2026
published: true
labels:
  - TypeScript
  - HTML
  - CSS
  - GitHub Pages
summary: "A guitar practice tracker I designed and built with ChatGPT assistance to organize practice sessions, set goals, and track progress."
---

<img class="img-fluid" src="../img/fret-notes.png" alt="Fret Notes guitar practice tracker showing the session form and practice progress">

[Try Fret Notes Here:](https://rockymacasio.github.io/fret-notes/) 
Fret Notes is a guitar practice tracker that connects my interest in playing guitar with software development. I wanted a way to keep track of what I practiced instead of just remembering how long I played. The app lets me log practice time, write notes, and organize sessions into songs, scales, technique and accuracy, fretboard and theory knowledge, or miscellaneous practice.

I developed this project with ChatGPT's help in generating and updating the code. My role focused on deciding what the app should do, trying the interface, and requesting changes that would make it more useful for my own practice. I proposed the practice categories,  progress levels, searchable history, weekly goals, practice streaks, and weekly recap. These additions made it easier to see both what I was learning and how consistently I was practicing.

<img class="img-fluid" src="../img/fret-notes-weekly.png" alt="Fret Notes weekly goals, practice streak, and weekly recap">

The app uses TypeScript for its logic, HTML for its structure, and CSS for its appearance. The TypeScript source is converted into JavaScript so it can run in a browser. Practice sessions and goals are saved using localStorage, so they remain available after refreshing the page on the same browser. The weekly recap groups practice by category and activity, while the streak counts consecutive practice days. I published the app using GitHub Pages.

One takeaway from this project was how much a small app can change through feedback. The first version was a simple practice log, but each change helped it fit the way I wanted to use it. It also gave me a practical example of how typed objects, arrays, forms, and browser storage work together in an application. 

With this project, I am able to log in my progress more efficiently and I can track how much progress I've made since starting this application. Further down the road, I would like to try and shift this into a mobile application where you can synchronously link your data from the website onto your phone to track progress wherever you are, no matter the device. This application does need some more revisions that I will hopefully work on in the future to use as a reference point in software development, but for now it serves as an efficient tool in being a tracker for progressing my guitar skills.

[View the source code](https://github.com/rockymacasio/fret-notes)
