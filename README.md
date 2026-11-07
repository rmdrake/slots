# Lucky Slots: A Study in Deviation

This repository contains a collection of various implementations of a single slot machine game. While every version in this project originated from the same foundational specification, they each represent a significant creative or technical deviation from that original plan.

## The Project Concept

The project began with a structured development plan (see [plan.md](plan.md)) that outlined a "standard" version of the game:
- **Core Mechanics**: 1000 starting credits, 100 credits per spin, with payouts for two-of-a-kind and three-of-a-kind.
- **Visuals**: A space/fantasy inspired theme using emoji symbols.
- **Technical Specs**: A single-file HTML/CSS/JS architecture utilizing the Web Audio API.

Instead of building just one version, this project evolved into an exploration of how small changes in theme, audio, and visual density can completely transform the user experience.

## The Versions

Each file in this repository is a standalone playable game. You can open any of them directly in a modern web browser.

| File | Theme / Deviation | Description |
| :--- | :--- | :--- |
| `slots_muse.html` | **Standard** | The baseline implementation following the original plan closely. |
| `slots_flashy.html` | **High-Energy** | Focuses on intense visual feedback and CSS animations. |
| `slots_sexy.html` | **Provocative** | A thematic departure using adult-oriented emojis and vertical reel strips. |
| `slots_noisy.html` | **Audio-Centric** | Prioritizes melodic audio sequences and a "glassmorphic" UI design. |
| `slots_simple.html` | **Minimalist** | Stripped down to the bare essentials for maximum performance and clarity. |
| `slots_royal.html` | **Space Fantasy** | A heavily themed version with a specific aesthetic and glowing animations. |
| `slots_enhanced.html` | **Feature-Rich** | An extreme version of visual effects, including twinkling star backgrounds. |
| `slots_neat.html` | **Modern/Polished** | A clean, professional take on the game with a sophisticated layout. |

## Technical Implementation

All versions leverage modern web technologies to ensure they are lightweight and require no external dependencies:
- **HTML5**: Semantic structure and responsive layouts.
- **CSS3**: Complex animations, gradients, and advanced layout techniques (Flexbox, Grid).
- **JavaScript (ES6+)**: Game logic, state management, and dynamic DOM manipulation.
- **Web Audio API**: Procedural sound generation using oscillators and gain nodes for real-time audio feedback.

## How to Play

1. Clone or download this repository.
2. Open any `slots_*.html` file in your preferred web browser.
3. Use the **SPIN** button to play. 
4. Watch your credits, wins, and losses!

---
*This project is an experiment in how design choices—from audio frequency to CSS animation timing—alter the perception of simple game mechanics.*
