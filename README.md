# Asset Portfolio Tracker

A comprehensive web-based application for tracking and managing diverse investment portfolios, including stocks, bonds, gold, and cash assets in multiple currencies.

## Features

- **Multi-asset Portfolio Management**: Track stocks, bonds, gold, and cash/other assets in one place
- **Real-time Market Data**: Automatically fetch current stock prices and gold prices from external APIs
- **Currency Conversion**: Support for multiple currencies with up-to-date exchange rates
- **Comprehensive Analytics**: View portfolio allocation, performance metrics, and gain/loss statistics
- **Responsive Design**: Fully functional on both desktop and mobile devices
- **Export Functionality**: Export your portfolio data to Excel format for external analysis
- **Offline Capability**: Continue working with cached data when offline
- **Customizable Themes**: Choose from multiple visual themes to suit your preference

## Technology Stack

- HTML5, CSS3 (with Tailwind CSS and DaisyUI)
- Vanilla JavaScript (no framework dependencies)
- Chart.js for data visualization
- SheetJS for Excel export functionality
- External APIs integration:
  - Finnhub API for stock market data
  - Gold Price API for precious metals pricing
  - Exchange Rate API for currency conversion

## Getting Started

Simply open the `index.html` file in any modern web browser to start using the application. No server setup or installation required!

### Adding Assets

1. Navigate to the appropriate tab (Stocks, Bonds, Gold, or Cash)
2. Click the "Add" button in the top right corner
3. Fill in the required details in the form
4. Click "Add" to save the asset to your portfolio

### Tracking Performance

- Use the "Refresh" button to update current market prices
- View portfolio metrics at the top of the page
- Explore the "Portfolio Overview" tab for detailed analytics

## Data Storage

All portfolio data is stored in your browser's local storage. To prevent data loss:
- Use the "Export Data" option to back up your portfolio regularly
- Avoid clearing browser data without exporting first

## Privacy

This application processes all data locally within your browser. No data is sent to any server except when fetching market prices and exchange rates from public APIs.

## License

This project is available as open source under the terms of the MIT License.

