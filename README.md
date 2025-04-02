Asset Portfolio Tracker - User Manual
Overview
Asset Portfolio Tracker is a web-based application that helps you track your investments across different asset classes including stocks, bonds, and cash. All data is stored locally in your browser, ensuring your financial information remains private.

Getting Started
Accessing the Application
You can access the application through your web browser at the URL where you've deployed it (e.g., https://yourusername.github.io/portfolio-tracker/).

Navigation
The application is organized into four main tabs:

Stocks: Track your stock investments
Bonds: Track your bond investments
Cash & Others: Track cash and other assets (e.g., savings accounts, cryptocurrencies)
Portfolio Overview: View charts, allocation, and performance metrics
You can switch between tabs using either:

The tab bar at the top of the page
The sidebar menu (accessible via the hamburger menu on mobile)
Adding Assets
Adding Stocks
Navigate to the Stocks tab
Click the Add Stock button
Enter the following information:
Stock Symbol (e.g., MSFT for Microsoft)
Number of Shares
Purchase Price Per Share
Purchase Date
Click Add Stock
The application will automatically fetch the current price and company name from Alpha Vantage API.

Adding Bonds
Navigate to the Bonds tab
Click the Add Bond button
Enter the following information:
Bond Name
Type (Government, Municipal, Corporate, Other)
Face Value
Purchase Price
Yield (%)
Maturity Date
Click Add Bond
Adding Cash & Other Assets
Navigate to the Cash & Others tab
Click the Add Asset button
Enter the following information:
Asset Name
Type (Cash, Savings, CD, Cryptocurrency, Other)
Value
Currency
Optional Notes
Click Add Asset
Managing Assets
Editing Assets
Find the asset you want to edit in its respective tab
Click the pencil (edit) icon
Make your changes in the edit form
Click Save Changes
Deleting Assets
Find the asset you want to delete in its respective tab
Click the trash (delete) icon
The asset will be removed immediately
Searching for Stocks
In the Stocks tab, use the search box to filter stocks by name or symbol
Click the X button to clear the search
Refreshing Stock Prices
To update stock prices with the latest market data:

Click the refresh icon in the top right corner of the application
A notification will appear showing how many stocks were successfully updated
The portfolio summary will automatically recalculate
Note: The application uses the Alpha Vantage API with limited free tier access (5 calls per minute). If you have many stocks, some may fail to update.

Currency Conversion
For cash assets in non-USD currencies:

The application automatically converts all currencies to USD for the portfolio summary
Original currency values are shown in the Cash tab
Exchange rates are fetched from the Open Exchange Rates API
You can view and update exchange rates in the Portfolio Overview tab
Theme Settings
To change the application theme:

Click the palette icon in the top right corner
Select from available themes: Light, Dark, Corporate, or Business
The theme will be saved for your next visit
Portfolio Overview Features
The Portfolio Overview tab provides:

Asset Allocation: A pie chart showing the distribution of your assets across stocks, bonds, and cash
Top Performers: Your best-performing investments by percentage gain
Worst Performers: Your poorest-performing investments by percentage loss
Asset Summary: A table showing the count, value, and allocation percentage of each asset class
Exchange Rates: Current currency exchange rates used for calculations
