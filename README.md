# Sales Summary App

## Summary
This is a simple single-page application that fetches sales data from a CSV file and displays the total sales.

## Setup
1. Clone the repository.
2. Open `index.html` in a web browser.

## Usage
The app will automatically fetch `data.csv`, calculate the total sales, and display it on the page.

## Code Explanation
- The app uses the Fetch API to retrieve `data.csv`.
- It processes the CSV data, summing the sales column using `parseFloat` for numeric computations.
- The total is displayed in the `#total-sales` div.

## License
This project is licensed under the MIT License.

## Description
This app demonstrates how to fetch and process CSV data in a web application while ensuring proper numeric validation.