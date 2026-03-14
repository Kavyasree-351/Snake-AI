# Snake AI — Neuroevolution

> NEAT-inspired neuroevolution agent that learns to play Snake 
> in real-time — built with vanilla JS, zero libraries.

🎮 **[Play it live here](https://kavyasree-351.github.io/Snake-AI/)**

---

## What is this?

A population of 50 snake agents starts with completely random 
neural networks. Through natural selection and mutation across 
generations, they gradually learn to play Snake — no hardcoded 
rules, no training data. Pure evolution.

## How it works

**Each snake has a brain — a neural network with:**
- 8 inputs (danger sensors + food sensors in 4 directions)
- 12 hidden neurons
- 4 outputs (up, down, left, right)

**Each generation:**
1. All 50 snakes play simultaneously
2. Snakes that survive longer and eat more score higher
3. Best performers reproduce with slight random mutations
4. Next generation is slightly smarter than the last

## Features
- Real-time neural network visualisation
- Live sensor input display
- Score history per generation
- Adjustable simulation speed
- Population of 50 agents evolving simultaneously

## Architecture
```
Input (8) → Hidden (12) → Output (4)
Danger ↑↓←→ + Food ↑↓←→ → Move decision
```

## Built with
- Vanilla JavaScript — zero external libraries
- HTML5 Canvas for rendering
- Fully runs in the browser

---
*by Kavyasree · BITS Pilani Dubai*
