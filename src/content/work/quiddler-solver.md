---
title: Quiddler Solver
featured: true
featuredOrder: 3
publishDate: 2022-06-01 00:00:00
img: /assets/quiddler_solver.png
img_alt: The homepage of Quiddler Solver, showing an example of the highest score for a 7 card hand
description: |
  Find the highest possible score, given a hand in the card game Quiddler
tags:
  - Svelte
  - Service Worker
  - Open Source
---

This project is a Svelte application designed to maximize players' scores in Quiddler, a card game similar to Scrabble but played with letters to form words. The app calculates the highest possible score for any given hand by analyzing and permuting the letters provided by the user.
It identifies all possible permutations, including various word groups, and then verifies these groups against a dictionary to determine if they are  valid words.

As a bonus it also uses a Dictionary API to fetch the definition of the words that were found.

#### Technologies Used:

Single Page Application built with Svelte. 

#### Project Highlights:

Service Worker: The project uses a service worker to offload the permutation work so that it can be run in the background and not freeze the main UI thread.

Animation: Used the FLIP animation technique to create fluid animation sequences that are visually appealing. 

#### Conclusion:

Although this was a small project, it still involved using some mathematics to generate all the permutations and careful use of algorithms to ensure performance. 

I learn't how to use service workers to process data in the background, and show updates in the app as the service worker makes progress with its task.
