# gusedx.github.io
Summary of my personal projects

## **Current projects:**
- **TravelPlanningAgent**

    *Overview & Goals:*
  
      Travel Planning Agent is an AI-powered full-stack web application designed to simplify the entirety of the travel   itinerary creation process. The goal of this project is to provide a central hub where users can effortlessly manage travel destinations, explore specific places with instant AI-generated insights, and automatically construct structured daily itineraries.

    *Main Features:*
    
      - **Destinations Management**: Add, view, edit, and delete travel destinations
      - **Places to Visit**: For each destination, manage a list of places you want to visit and track the expected duration for each
      - **AI Location Overviews**: Instantly generate detailed descriptions and insights for any place using a Large Language Model
      - **Smart Itinerary Generation**: Automatically generate and save detailed, structured, day-by-day travel itineraries based on selected places and your desired trip duration
      - **Notes**: Add detailed personalized notes for each place you plan to visit
      - **Interactive UI**: Drag and drop functionality to reorder items
      - **Responsive Design**: Works perfectly on both desktop and mobile devices
  
    *Technology Stack:*
  
      - **Frontend**: React, Next.js, TypeScript, CSS Modules
      - **Backend**: Python, Flask
      - **Database**: MongoDB
      - **AI Integration**: Configured GenAI API
      - **Containerization**: Docker & Docker Compose
  
- **InvestmentTracker**
   
      *Overview & Goals:*

        A full-stack web application for tracking ETF (Exchange-Traded Fund) investments and transactions.
   
        Investment Tracker helps individual investors monitor their ETF portfolios in one place. The primary goals are:
   
         - Portfolio visibility – maintain a clear record of all buy/sell transactions across multiple ETFs.
         - Real-time price data – fetch live ETF prices and display 1-day, 1-month, and 1-year percentage changes via the [EODHD](https://eodhd.com/) financial data API.
         - Profit & Loss analysis – calculate the current value of savings/investments based on historical transactions and a configurable interest rate.
         - Holdings distribution – visualise the percentage split of holdings across different ETFs.
         - Multi-portfolio support – organise data into separate named files so multiple portfolios can be tracked independently.
   
      *Main Features:*
   
         | Feature | Description |
         |---|---|
         | **ETF Management** | Add and delete ETFs tracked in a portfolio file |
         | **Transaction Management** | Add, view, and delete individual buy/sell transactions |
         | **Excel Import** | Upload an `.xlsx` / `.xls` file to bulk-import transactions |
         | **ETF Price Search** | Look up the latest price and percentage changes (1D / 1M / 1Y) for any ETF symbol |
         | **Holdings Summary** | Pie/bar chart showing the percentage distribution of ETF holdings |
         | **Profit & Loss** | Compute the current value of a savings plan based on past transactions and an interest rate |
         | **File Management** | Create and switch between multiple portfolio data files |
   
         Excel Import Format
   
         Upload a spreadsheet with the following columns:
         
         | Column | Description | Example |
         |--------|-------------|---------|
         | Type   | `Buy` or `Sell` | `Buy` |
         | ETF    | ETF ticker symbol | `VWCE` |
         | Units  | Number of units | `10` |
         | Price  | Price per unit | `85.50` |
         | Date   | Transaction date (`YYYY-MM-DD`) | `2024-01-15` |
   
      *Technology Stack:*
   
      -**Backend:**
         - ASP.NET Core 8 – REST API
         - C# / .NET 8
         - EPPlus – Excel file parsing
         - CsvHelper – CSV data handling
         - System.IO.Abstractions – testable file-system abstraction
         - Swashbuckle / Swagger – API documentation
         - MSTest – unit testing
   
       -**Frontend:**
         - Angular 15 – SPA framework
         - Angular Material 15 – UI component library
         - Chart.js 4 – data visualisation (holdings charts)
         - TypeScript 4.9
         - Karma / Jasmine – unit testing
   
       -**External Services:**
         - [EODHD API](https://eodhd.com/) – real-time and historical ETF price data (free tier supported)
     
- **GarminAnalysis**
    
  *Technology Stack:*
  
      - Frontend: 
      - Backend: 

**Older projects:**
- chat-application
