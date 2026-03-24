# Corgi Run

An infinite runner game developed with a focus on performance and user experience, created with both a personal and technical purpose.

## The Story Behind the Code
I developed this project during a trip as a way to connect with my girlfriend. Knowing her admiration for Corgis, I used programming to create an interactive experience that could bridge the distance while I was away. This project demonstrates my ability to identify real human motivations and transform them into functional, engaging products.

## Technical Highlights
* **Dynamic Day/Night Cycle:** The game features a real-time environment transition based on the player's score, changing background colors, obstacle types (shifting from cacti to ghosts), and visual effects like shooting stars.
* **Procedural Audio:** I implemented jump and game-over sound effects using the Web Audio API (AudioContext), generating audio through code rather than relying on external files.
* **Data Persistence:** The game utilizes LocalStorage to save and track the player's high score locally.
* **Responsiveness:** The layout is fully responsive, featuring a fluid design and touch-action manipulation for mobile devices.

## How to Play
* **Objective:** Help the Corgi dodge obstacles and survive as long as possible.
* **Controls:** Press the Spacebar, click the mouse, or tap the screen to jump.
* **Progression:** The game speed increases gradually as the score rises.

## Tech Stack
* **HTML5:** Game structure and DOM organization.
* **CSS3:** Complex animations, native CSS variables (:root), and responsive layout.
* **JavaScript (Vanilla):** Physics logic (gravity and collision detection), rendering loop, and audio processing.

## Live Demo
The game can be accessed and played directly in the browser:
[Play Corgi Run](https://lspradoo.github.io/Corgi_Game/)

---
Developed by Lucas Prado.