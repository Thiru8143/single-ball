# Moving Ball Animation

This is a simple webpage that animates a ball moving diagonally across the screen. The ball bounces back when it reaches the edges of the viewport.

## Technologies Used
- **HTML5**: Structure of the webpage.
- **CSS**: Styling the ball.
- **JavaScript**: Handling the ball's movement.

## Features
- A ball that moves diagonally across the screen.
- The ball changes direction when it hits the screen's boundary.
- Smooth animation using JavaScript `setInterval`.

## How to Use
1. Clone or download the repository.
2. Open the `index.html` file in any modern browser.
3. Watch the ball move and bounce around the screen!

## Code Explanation

- **HTML**: 
  - The `<div>` element represents the ball. It's positioned absolutely on the page.

- **CSS**: 
  - The ball is styled to have a `border-radius` of `50%` to make it circular. The initial size and position are set in the `style` attribute of the `<div>`.

- **JavaScript**: 
  - The `movingBall` function updates the ball's position at regular intervals using `setInterval`.
  - The ball moves diagonally across the screen by adjusting its `top` and `left` properties.
  - When the ball reaches the edge of the viewport, its direction is reversed.

## Installation

No installation required. Simply open the `index.html` file in a browser.

## Future Enhancements
- Add more interactive features, like controlling the ball's speed.
- Implement smoother animations using `requestAnimationFrame`.
- Add touch or mouse controls to move the ball manually.

## License
This project is open-source and available under the MIT License.
