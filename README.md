# Memory Card Matching Game

This is an interactive memory card matching game built using React. The game challenges players to find matching pairs of cards within a limited time and number of flips, offering an engaging experience for users across various devices.

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Deployment](#deployment)
- [Technologies Used](#technologies-used)
- [Learnings & Experiences](#learnings--experiences)

## Demo

Check out the live demo of the game [here](https://memory-cards-reactgame.netlify.app).

## Features

- **Responsive Design:** The game is fully responsive, providing an optimal experience on both mobile and desktop devices.
- **Dynamic Gameplay:** The game includes a 2-minute timer, a maximum of 5 unsuccessful flips, and a 'Play Again' functionality that shuffles the cards after each round.
- **Sound Effects:** Integrated sound effects for winning and game over, enhancing the user experience.
- **Engaging UI:** The game features a sleek grid design, a gradient background, and smooth card flip animations.
- **Score Tracking:** The game tracks the number of matches made and the flips remaining, giving users real-time feedback.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/AryanAgrawal2207/memory-card-game.git
   cd memory-card-game
2. **Install dependencies:**
   ```bash
   npm install
3. **Run the development server:**
   ```bash
   npm start
4. **Build the project for production:**
   ```bash
   npm run build
   
## Usage
Visit http://localhost:3000 in your browser to view the game.
Flip the cards to find matching pairs within the time limit.
Customize the game by modifying the content in the src folder.

## Deployment

1. **Deploy to Netlify:**
   Install Netlify CLI if not already installed:
   ```bash
   npm install -g netlify-cli

2. **Deploy the build folder:**
   ```bash
   netlify deploy --dir=build --prod

## Technologies Used
React: JavaScript library for building user interfaces
CSS: Styling for the game layout and animations
Web Audio API: For integrating sound effects
Netlify: Platform for deploying and hosting the web app

## Learnings & Experiences
React Development: Enhanced my understanding of React hooks, state management, and component-based architecture.
Responsive Design: Learned how to create a responsive layout that works seamlessly across different screen sizes.
Sound Integration: Gained experience in integrating sound effects using the Web Audio API, enriching the overall gameplay.
Deployment: Acquired knowledge on deploying React applications to Netlify, ensuring smooth live performance.
