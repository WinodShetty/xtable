# XTable React Application

This project is a simple React application that displays a table of articles with dates and views. The table can be sorted by date or views using buttons. The application demonstrates basic React state management, sorting functionality, and rendering a dynamic table.

## Application Requirements

The application renders a table with the following data:

```javascript
[
    { date: "2022-09-01", views: 100, article: "Article 1" },
    { date: "2023-09-01", views: 100, article: "Article 1" },
    { date: "2023-09-02", views: 150, article: "Article 2" },
    { date: "2023-09-02", views: 120, article: "Article 3" },
    { date: "2020-09-03", views: 200, article: "Article 4" }
]


Sorting Requirements
Sort by Date:

When the "Sort by Date" button is clicked, the table is sorted so that rows with the most recent dates appear at the top.
If multiple rows have the same date, they are further sorted by views in descending order.
Sort by Views:

When the "Sort by Views" button is clicked, the table is sorted by views in descending order.


Here’s a README.md file for your React application:

markdown
Copy code
# XTable React Application

This project is a simple React application that displays a table of articles with dates and views. The table can be sorted by date or views using buttons. The application demonstrates basic React state management, sorting functionality, and rendering a dynamic table.

## Application Requirements

The application renders a table with the following data:

```javascript
[
    { date: "2022-09-01", views: 100, article: "Article 1" },
    { date: "2023-09-01", views: 100, article: "Article 1" },
    { date: "2023-09-02", views: 150, article: "Article 2" },
    { date: "2023-09-02", views: 120, article: "Article 3" },
    { date: "2020-09-03", views: 200, article: "Article 4" }
]
Sorting Requirements
Sort by Date:

When the "Sort by Date" button is clicked, the table is sorted so that rows with the most recent dates appear at the top.
If multiple rows have the same date, they are further sorted by views in descending order.
Sort by Views:

When the "Sort by Views" button is clicked, the table is sorted by views in descending order.
Installation
To run the project locally, follow these steps:

Clone the Repository:

bash
Copy code
git clone https://github.com/your-username/xtable-react-app.git
cd xtable-react-app
Install Dependencies:
Make sure you have Node.js installed. Then, install the project dependencies using npm or yarn:

bash
Copy code
npm install
# or
yarn install
Start the Development Server:
Start the application in development mode:

bash
Copy code
npm start
# or
yarn start
The app should open in your default web browser at http://localhost:3000.

Project Structure
src/XTable.js: This file contains the main component that handles the state and rendering of the table. The component also contains the sorting functions that are attached to the buttons.
How to Use
Sort by Date:

Click the "Sort by Date" button to sort the table so that the most recent dates are displayed first. If multiple rows share the same date, they will be further sorted by views in descending order.
Sort by Views:

Click the "Sort by Views" button to sort the table by the number of views in descending order.
