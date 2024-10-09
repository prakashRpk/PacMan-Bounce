# PacMan Bounce

This project is a simple interactive web application where users can add "PacMan" images that move around the screen and bounce off the edges. The application demonstrates basic HTML, CSS, and JavaScript functionalities, including DOM manipulation and animation.

## Demo

You can view a live demo of the project [here](#).  
*(Replace the `#` with the URL to your hosted project, if available.)*

## Features

- Add multiple "PacMan" images by clicking the "Add PacMan" button.
- Each image moves and bounces off the window edges.
- Simulates gravity to create a realistic bouncing effect.
- Responsive design that adjusts based on window size.

## How It Works

1. **Adding PacMan Images**:
   - When the "Add PacMan" button is clicked, a new PacMan image is created at a random position on the screen with randomized velocity.
  
2. **Movement**:
   - The PacMan images continuously move across the screen.
   - When they reach the edges of the window, they bounce back in the opposite direction.
   - Gravity is simulated by gradually increasing the vertical velocity of the images.

3. **Animation**:
   - The movement is handled using `requestAnimationFrame` for smooth animations.

## Installation

To run this project locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/pacman-bounce.git
   cd pacman-bounce
   open index.html
 ## Usage
Once you open the project in your browser, you can click the "Add PacMan" button to create PacMan images that will start moving around the screen. You can add as many as you like!

## Customization
You can change the PacMan image by modifying the img.src value in the JavaScript code.
Adjust the speed and gravity values in the JavaScript code to change the movement dynamics.
Update the dimensions of the PacMan images by modifying the img.style.width and img.style.height properties.
