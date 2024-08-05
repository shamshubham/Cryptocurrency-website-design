# Cryptocurrency Price Tracker

This project is a simple web page that displays the current prices of major cryptocurrencies, including Bitcoin, Ethereum, and Dogecoin. The prices are fetched in real-time using the CoinGecko API and displayed on the page.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Code Overview](#code-overview)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Introduction

The Cryptocurrency Price Tracker provides real-time updates of cryptocurrency prices. The simple, user-friendly design displays the current price of popular cryptocurrencies and offers an engaging experience for users interested in the crypto market.

## Getting Started

### Prerequisites

- A modern web browser (e.g., Chrome, Firefox, Safari)
- Basic understanding of HTML, CSS, JavaScript, and jQuery

### Installation

1. **Clone the Repository**:

   ```bash
   git clone <repository-url>
   cd cryptocurrency-price-tracker
   ```

2. **Open the Project**:

   Open the `index.html` file in your web browser to view the cryptocurrency prices.

## Usage

Simply open the `index.html` file in a web browser. The page will automatically fetch and display the current prices of Bitcoin, Ethereum, and Dogecoin using the CoinGecko API.

## Code Overview

### 1. HTML Structure

The `index.html` file sets up the basic structure of the web page, including a navigation bar, a content section with a promotional message, and a list of cryptocurrencies with their current prices.

### 2. CSS Styling

The CSS file (`style.css`) styles the navigation, content, and cryptocurrency list sections to create a modern and responsive layout.

### 3. JavaScript Functionality

The JavaScript functionality (`script.js`) handles fetching and displaying the cryptocurrency prices:

- **API Fetching**: The `$.ajax` method is used to call the CoinGecko API and retrieve the current prices of Bitcoin, Ethereum, and Dogecoin in USD.
- **DOM Manipulation**: The fetched prices are then displayed on the page by updating the inner HTML of specific elements with the corresponding price data.

### 4. jQuery

The project uses jQuery for ease of making API requests and manipulating the DOM.

## Technologies Used

- **HTML5**: Structure and layout of the website.
- **CSS3**: Styling and responsive design.
- **JavaScript**: Functionality for fetching and displaying data.
- **jQuery**: Simplifying DOM manipulation and AJAX requests.
- **CoinGecko API**: Source of real-time cryptocurrency prices.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please fork the repository and create a pull request. For significant changes, please open an issue to discuss your ideas.

## License

This project is licensed under the MIT License.

## Acknowledgments

- Thanks to CoinGecko for providing a free API for cryptocurrency prices.
- Special thanks to the open-source community for providing tools and resources.
