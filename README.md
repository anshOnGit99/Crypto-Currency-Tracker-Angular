# Crypto Currency Tracker

## Overview

The **Crypto Currency Tracker** is an Angular-based web application that allows users to track the latest updates and trends in the cryptocurrency market. The application provides real-time data on various cryptocurrencies, including their current prices, market caps, and price changes over the last 24 hours. Users can also view detailed information about individual cryptocurrencies, including historical price trends over different time periods (24 hours, 30 days, 90 days, and 1 year).

The application integrates with the **CoinGecko API** to fetch real-time cryptocurrency data and uses **Angular Material** for a sleek and responsive user interface. Users can switch between different currencies (INR and USD) to view the data in their preferred currency.

## Features

- **Real-Time Cryptocurrency Data**: Fetches real-time data from the CoinGecko API, including current prices, market caps, and 24-hour price changes.
- **Currency Conversion**: Allows users to switch between INR and USD to view cryptocurrency data in their preferred currency.
- **Trending Cryptocurrencies**: Displays a marquee of trending cryptocurrencies with their price changes over the last 24 hours.
- **Detailed Coin Information**: Provides detailed information about individual cryptocurrencies, including historical price trends.
- **Interactive Charts**: Displays interactive line charts for historical price trends over different time periods (24 hours, 30 days, 90 days, and 1 year).
- **Search and Filter**: Users can search and filter the list of cryptocurrencies by name or symbol.
- **Responsive Design**: The application is fully responsive and works seamlessly across different devices.

## Technologies Used

- **Angular**: A TypeScript-based web application framework used for building the front-end of the application.
- **Angular Material**: A UI component library for Angular that provides a wide range of pre-built, customizable components.
- **CoinGecko API**: A free API that provides real-time and historical data on cryptocurrencies.
- **Chart.js**: A JavaScript library used for rendering interactive charts in the application.
- **RxJS**: A library for reactive programming using Observables, used for handling asynchronous data streams.
- **HTML5 & SCSS**: Used for structuring and styling the application.

## Installation

To run the Crypto Currency Tracker locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/crypto-currency-tracker.git
   cd crypto-currency-tracker
2. **Install Dependencies:**
   ```bash
   npm install
3. **Run the Application:**
   ```bash
   ng serve
4. **Open the Application:**<br>
   Navigate to http://localhost:4200/ in your browser to view the application.

# Usage

**Home Page**: The home page displays a list of cryptocurrencies with their current prices, 24-hour price changes, and market caps. Users can search and filter the list using the search bar.<br>
**Trending Cryptocurrencies**: A marquee at the top of the home page displays trending cryptocurrencies with their price changes over the last 24 hours.<br>
**Currency Conversion**: Users can switch between INR and USD using the currency selector in the toolbar.<br>
**Coin Details**: Clicking on a cryptocurrency from the list navigates to a detailed view, where users can see more information about the coin, including historical price trends.<br>

# Contributing
Contributions are welcome! If you'd like to contribute to the project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Make your changes and commit them with descriptive messages.
4. Push your changes to your forked repository.
5. Submit a pull request to the main repository.

# License
This project is licensed under the MIT License. See the LICENSE file for more details.
