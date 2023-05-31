# Random Quote Generator

This project is a simple web application that generates random quotes and displays them on the webpage. It fetches quotes from an external API and updates the quote and author sections dynamically.

## Usage

To use this application, follow these steps:

1. Clone the repository or download the source code files.
2. Open the `index.html` file in a web browser.

## Files

The project consists of the following files:

- `index.html`: This is the main HTML file that contains the structure and content of the webpage.
- `script.js`: This JavaScript file handles the fetching of quotes from the API and updating the quote and author sections on the webpage.
- `style.css`: This CSS file contains the styling rules for the webpage.

## Dependencies

The project has the following dependencies:

- [Google Fonts](https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap): This is an external font library used to style the text on the webpage.

## How it Works

1. When the webpage loads, it calls the `getQuote` function to fetch a random quote from the API and display it on the webpage.
2. The `getQuote` function uses the `fetch` function to make a GET request to the API endpoint (`https://api.quotable.io/random`) and receives a JSON response.
3. The JSON response contains the content of the quote and the author's name. The `getQuote` function updates the `quote` and `author` elements on the webpage with the fetched data.
4. The webpage also includes a "Get Quote" button. When the button is clicked, it triggers the `getQuote` function to fetch a new quote and update the webpage.

## Styling

The styling of the webpage is defined in the `style.css` file. It includes the following styles:

- `body`: Sets the background color to `#9135f4`.
- `.wrapper`: Positions the container in the center of the page.
- `.container`: Styles the quote container with a background color of `#9135f4`, padding, box-shadow, and other properties.
- `.container p`: Styles the quote text with a color of `#fdd8d8`, font size, and line height.
- `.container h3`: Styles the author text with a color of `#ffffff`, margin, font weight, and text transformation.
- `.container button`: Styles the "Get Quote" button with a background color of `#ffffff`, padding, border radius, font size, font weight, and color.

Feel free to modify the CSS styles in the `style.css` file to customize the appearance of the webpage.

## API

The project uses the [Quotable API](https://api.quotable.io/) to fetch random quotes. The API returns a JSON response containing the quote content and author's name.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to modify and use the code for your own projects.
