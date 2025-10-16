# Sales Summary Dashboard

This is a single-page, responsive web application built with HTML, Tailwind CSS, and vanilla JavaScript. It fetches sales data from a local `data.csv` file, parses and displays all the data in a tabular format, and calculates the total sales.

## Features

*   Fetches `data.csv` asynchronously.
*   Parses CSV data to extract all rows and columns.
*   Dynamically renders a responsive HTML table to display all data.
*   Calculates and prominently displays the sum of all sales.
*   Dynamically updates the page title to "Sales Summary {Year}".
*   Responsive design using Tailwind CSS.

## Getting Started

To run this application, you only need a web browser.

### Prerequisites

No specific software is required beyond a modern web browser.

### Installation

1.  **Save the files:** Ensure `index.html` and `data.csv` are in the same directory.
2.  **Open `index.html`:** Simply open the `index.html` file in your web browser.

The application will automatically fetch `data.csv`, process it, display the data in a table, and show the total sales.

## `data.csv` Format

The `data.csv` file is expected to be a comma-separated values file with a header row. It **must** contain a column named `sales` for the total sales calculation to function correctly.

Example `data.csv` structure:

```csv
id,item,sales
1,Product A,100.50
2,Product B,250.75
3,Product C,120.00
```

## Technologies Used

*   **HTML5:** Structure of the web page.
*   **Tailwind CSS:** For styling and responsive design. (CDN included)
*   **JavaScript (Vanilla):** For data fetching, parsing, and DOM manipulation.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
