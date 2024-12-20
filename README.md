# Shuffling Project

## About this Project
This project is a simple HTML, CSS, and JavaScript web page that displays a list of people assigned to various rooms and beds. 
The main feature of this webpage is a "Shuffle" button that randomizes the names within the list while keeping the room and bed assignments static.

## Project Structure
- **HTML**: Contains the structure of the webpage, including tables to display room and bed assignments.
- **CSS**: Styles the webpage to enhance its visual appearance.
- **JavaScript**: Provides functionality to shuffle the names within the tables when the "Shuffle" button is clicked.

## Files
- **index.html**: The main HTML file containing the structure of the webpage.
- **style.css**: The CSS file used to style the HTML elements.
  
## HTML
The HTML file includes multiple tables, each representing a room with assigned beds. Each table has the same structure, containing columns for serial number, name, room number, and bed number.

## Key Elements
- **Tables**: Each room's data is displayed in a separate table.
- **Shuffle Button**: A button that triggers the shuffling of names.

## CSS
The CSS file styles the webpage, including the tables and the shuffle button.

## Key Styles
- Body: The background color is set to wheat.
- Headers: Styled with specific colors and fonts.
- Tables: Given a border and spacing to make the data clear and organized.
- Table Headers (th): Background color set to goldenrod.
- Table Data (td): Background color set to gray and text color to black.
- Shuffle Button: Positioned and styled with a background color of palevioletred.

## JavaScript
The JavaScript code provides the functionality to shuffle the names within the tables when the shuffle button is clicked.

## Functionality
- Event Listener: Added to the shuffle button to trigger the shuffling function on click.

## Shuffling Algorithm:
- Collects all names from the tables.
- Shuffles the names using a random algorithm.
- Reassigns the shuffled names back to the table cells.

## How to Use
1. Open index.html in a web browser.
2. View the list of people assigned to various rooms and beds.
3. Click the **"Shuffle"** button to randomize the names within the list.
