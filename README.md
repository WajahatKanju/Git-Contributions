# LED Contribution Matrix

This project simulates a contribution grid similar to GitHub's contribution heatmap, with an LED display for visualizing characters. It dynamically generates a matrix of LEDs and allows rendering letters using a font-like pattern.

## Features

- **GitHub-style Contribution Calendar**: Shows a calendar grid with different color intensities based on contributions.
- **LED Matrix Display**: Displays characters on a custom grid of LEDs using pre-defined font patterns.
- **Customizable Contributions Legend**: A scale to visually represent contributions from "Less" to "More" using different color boxes.

## Demo

You can see a live version of the project by running it locally (instructions below).

## Getting Started

### Prerequisites

To run this project, you will need a modern browser and a text editor to view and modify the code.

### Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/led-contribution-matrix.git
    ```
2. Open the `index.html` file in your browser.

### Usage

- Open the project in your browser.
- The contribution grid is rendered automatically, showing months on the top and contribution days on the grid.
- The LED matrix below the calendar can render predefined letters such as A, B, C, etc.

### Customization

You can modify the LED matrix's behavior by adjusting the font patterns in the JavaScript object. To add new letters, modify the `font` object in the `script.js` file.

### File Structure

- `index.html`: The main HTML file that sets up the structure of the contribution grid and LED matrix.
- `style.css`: Contains styles for the contribution grid, LED matrix, and general layout.
- `script.js`: Defines the behavior of the LED matrix and contribution grid rendering.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Contributing

If you would like to contribute to this project, please feel free to submit a pull request or open an issue.

### Acknowledgments

- Inspired by GitHub's contribution heatmap design.