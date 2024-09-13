# Cooling Fan Project

This project simulates a moving fan using HTML, CSS, and JavaScript. You can control the speed of the fan, turn it on or off, and adjust its speed with different buttons.

## Features
- **Fan Animation**: The fan rotates continuously when turned on.
- **Speed Control**: Adjust the fan's speed with different buttons.
- **On/Off Functionality**: Start and stop the fan using dedicated buttons.

## Project Structure

- `index.html`: Contains the structure of the fan simulation, including buttons for controlling the fan.
- `style.css`: Defines the visual styles of the fan, including the rotation animation.
- `script.js`: Handles the logic for turning the fan on/off and adjusting its speed.

### HTML (index.html)
This file contains the basic structure of the project:
- A fan image (`img` tag) to represent the fan.
- Five buttons: 
  - **ON**: Turns the fan on.
  - **OFF**: Turns the fan off.
  - **1, 2, 3**: Set the fan's speed to low, medium, or high.

### CSS (style.css)
The CSS defines how the fan looks and rotates:
- A circular fan image with padding and border-radius to make it appear round.
- Keyframes are used to create the rotation animation (`@keyframes fananim`).

### JavaScript (script.js)
This script controls the fan's speed and on/off functionality:
- `myfunon()`: Starts the fan at a base speed.
- `myfunoff()`: Stops the fan by setting the animation duration to zero.
- `myfun2()`, `myfun3()`, `myfun4()`: Adjust the fan's speed to slow, medium, and fast respectively.

## How to Run
1. Download or clone the repository.
2. Open `index.html` in your web browser.
3. Use the buttons to control the fan's speed and turn it on or off.

Here is the live Demo [here](https://shivu0008.github.io/Cooling-Fan/)
