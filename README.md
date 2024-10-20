# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh



KB-Currency Converter

Welcome to the KB-Currency Converter project! This is a frontend application that allows users to convert between different currencies using real-time exchange rates fetched from a public API. Built using React and Tailwind CSS, this project simulates a real-world development environment and showcases how to integrate external APIs, handle user inputs, manage state, and build responsive, user-friendly interfaces.

Table of Contents

Project Overview
Features
Technologies Used
Setup Instructions
Usage
Error Handling
Future Improvements
License
Project Overview

The KB-Currency Converter allows users to:

Select two currencies (from and to) from a list.
Enter the amount they want to convert.
Fetch real-time exchange rates from an API.
Display the converted amount instantly.
The project is an excellent way to practice frontend web development, especially in integrating APIs, managing state with React, and building responsive, mobile-first applications using Tailwind CSS.

Features

Fetch Exchange Rates

Utilizes a public currency API like ExchangeRate-API to fetch real-time exchange rates.
Stores the exchange rates in the application state for quick access during conversions.
Currency Conversion

Users can select two currencies (from and to) from dropdown lists.
Provides an input field where users can enter the amount to convert.
Displays the converted amount dynamically based on the selected currencies and input value.
Exchange Rate Information

Shows the current exchange rate for the selected currency pair.
Optionally displays additional details such as the date of the last rate update.
Responsive UI Design

Built with Tailwind CSS to ensure a responsive design that works seamlessly on different devices (desktop, tablet, mobile).
Clean, user-friendly layout for the currency selection and conversion fields.
Error Handling

Handles scenarios like network failures, invalid API responses, or unsupported currencies gracefully.
Displays user-friendly error messages when issues occur, ensuring a smooth user experience.
Technologies Used

React: JavaScript library for building interactive user interfaces.
Tailwind CSS (optional): Utility-first CSS framework for creating responsive designs.
JavaScript (ES6): Core language for adding functionality.
HTML/CSS: Markup and styling.
ExchangeRate-API: API for fetching real-time exchange rates.
Setup Instructions

To run this project locally, follow these steps:

Clone the repository:
git clone https://github.com/kingsleyboateng/kb-currency-converter.git
Navigate to the project directory:
cd kb-currency-converter
Install dependencies:
npm install
Start the development server:
npm run dev
Open the app in your browser at http://localhost:5173.
Usage

Select a currency to convert from and to using the dropdowns.
Enter the amount you want to convert in the input field.
The converted amount will be displayed instantly.
The current exchange rate for the selected currencies will also be displayed.
Example

Select USD as the "From" currency.
Select EUR as the "To" currency.
Enter 100 in the input field.
The application will display the equivalent amount in EUR, along with the current exchange rate.
Error Handling

The application is designed to handle common issues such as:

Network Errors: If there's an issue connecting to the API, an error message will be displayed.
Invalid API Responses: If the API returns invalid data, a friendly alert will notify the user.
Unsupported Currencies: In case a user selects unsupported currencies, a clear message will be shown.
Future Improvements

Add support for more APIs to provide fallback options.
Include historical exchange rates and trend charts.
Implement user authentication for saving favorite currency pairs.
Add unit tests using tools like Jest and React Testing Library.
