# Word of the Day (Science Edition)

This project is a simple web application that displays a "Word of the Day" along with its definition. The application is designed with dynamic and vibrant color themes, making it visually appealing and suitable for presentations, such as classroom use or projecting on a screen.

## Features

- **Dynamic Color Themes**: A random color combination is selected each time the page is loaded, featuring 15 different color patterns, including tropical and vibrant options.
- **Interactive Word Input**: Users can input a word and its definition, which is then displayed in the same position as the input boxes for a seamless layout.
- **Projector-Friendly Design**: The title and displayed text are large and legible, making it perfect for projection or sharing with larger audiences.
- **Reset Option**: A "Done" button allows users to reset the form and start over easily.

## Technologies Used

- **HTML**: For the structure of the application.
- **CSS**: For styling, including dynamic themes and responsive design.
- **JavaScript**: For functionality, including random color generation, input handling, and dynamic content updates.

## Getting Started

### Prerequisites

To run this project, you need a modern web browser that supports HTML5, CSS3, and JavaScript.

### Installation

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/bronzewonka/word-of-the-day.git
   ```
2. Navigate to the project folder:
   ```bash
   cd word-of-the-day
   ```
3. Open the `index.html` file in your browser.

## Usage

1. Enter a word and its definition in the provided input fields.
2. Click the **Create** button to display the word as blanks (e.g., `_ _ _`) and the definition in large text.
3. The input fields will disappear, and the result will stay in place, ready for display.
4. To reset the page, click the **Done** button to clear the output and bring back the input fields.

## Color Themes

The application features 15 vibrant color combinations that are randomly applied on page load:

1. Blue & Pastel Pink
2. Dark Charcoal & Bright Yellow
3. Cherry Red & Off-White
4. Baby Blue & White
5. Sky Blue & Bubblegum Pink
6. Midnight Blue, Royal Blue, & Burgundy Red
7. Seafoam Green & Light Blue
8. Coral & Turquoise
9. Tropical Pink & Orange
10. Lime Green & Hot Pink
11. Sunset Yellow & Ocean Blue
12. Mango & Papaya
13. Coconut Brown & Palm Green
14. Turquoise & Sand Yellow
15. Pineapple Yellow & Mint Green

## Customization

- To add more color combinations, update the `colorOptions` array in the `setRandomColors` function in the `<script>` section of the HTML file.
- Adjust font sizes, margins, and layout styles in the CSS for further customization.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to improve the project.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Acknowledgments

- Thanks to the vibrant tropical vibes for inspiring the color themes.
- A special shoutout to project collaborators and users who make this project fun and exciting!

