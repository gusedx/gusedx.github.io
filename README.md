# gusedx.github.io
Summary of my personal projects

## **Current projects:**
**TravelPlanningAgent**

*Overview & Goals:*
  
Travel Planning Agent is an AI-powered full-stack web application designed to simplify the entirety of the travel   itinerary creation process. The goal of this project is to provide a central hub where users can effortlessly manage travel destinations, explore specific places with instant AI-generated insights, and automatically construct structured daily itineraries. The user can also search for flights and / or rail options for travel between two places at a specified date. Flight / train options including time and price are shown to the user. 

<img width="1912" height="826" alt="TravelPlanningAgentV2" src="https://github.com/user-attachments/assets/b872a06c-7a26-4de1-bc46-7320c295975e" />


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
  - **Testing**: Pytest, Jest, React Testing Library, Playwright

**TravelPlanningAgent**

*Overview & Goals:*

Designed to guide students and learners through complex concepts using the **Socratic method**. Instead of simply giving away answers or dumping dense paragraphs, the AI tutor asks targeted, thought-provoking questions, validates foundational knowledge step-by-step, and uses a locked-down web search tool (`.edu` and `wikipedia.org` only) to cross-check educational facts in real time.

<img width="1882" height="825" alt="TutorAgent" src="https://github.com/user-attachments/assets/a8ca3e41-2fb8-46ff-bc62-768c755344b1" />


*Main Features:*

- Socratic Dialogue Engine: Built using **LangGraph** and Google GenAI (`gemini-2.5-flash`), configured to stimulate critical thinking and active learning.
- Academic Grounding (Tavily Search): Constrained tool execution strictly scoped to verified educational domains (`site:edu` or `site:wikipedia.org`).
- Modern Responsive React UI:
  - Dark-mode interface built with React, TypeScript, Tailwind CSS, and Vite.
  - Rich Markdown Formatting: Preserves line breaks, styled tables, blockquotes, and lists.
  - Syntax-Highlighted Code Blocks: Code blocks rendered via `rehype-highlight` with one-click copy buttons.
  - Live Tool Execution Badges: Transparent, expandable badges showcasing whenever the agent conducts academic searches.
  - Quick-Start Prompts & Health Status: Interactive topic cards and real-time backend connection status indicator.
- FastAPI Backend: Clean asynchronous API with CORS support and flexible message payload processing.

*Technology Stack:*
   
- **Backend:**
  - Python 3.10+
  - LangChain / LangGraph: StateGraph orchestration for AI workflows and tool dispatching.
  - Google GenAI / Gemini 2.5 Flash: Core Large Language Model.
  - Tavily Search: Academic web retrieval.
  - FastAPI & Uvicorn: High-performance REST API backend.
  - Pydantic: Request/response schema validation.
  - python-dotenv: Environment variable management.

- **Frontend:**
  - React 18 & TypeScript
  - Vite: Ultra-fast build tool and local dev server with proxy support.
  - Tailwind CSS: Modern utility-first styling.
  - Lucide React: Modern iconography.
  - react-markdown, remark-gfm, remark-breaks: Markdown parsing with table support and single-newline breaks.
  - rehype-highlight: Code syntax highlighting.
  
**InvestmentTracker**
   
*Overview & Goals:*

A full-stack web application for tracking ETF (Exchange-Traded Fund) investments and transactions.
   
Investment Tracker helps individual investors monitor their ETF portfolios in one place. The primary goals are:
   
- Portfolio visibility – maintain a clear record of all buy/sell transactions across multiple ETFs.
- Real-time price data – fetch live ETF prices and display 1-day, 1-month, and 1-year percentage changes via the [EODHD](https://eodhd.com/) financial data API.
- Profit & Loss analysis – calculate the current value of savings/investments based on historical transactions and a configurable interest rate.
- Holdings distribution – visualise the percentage split of holdings across different ETFs.
- Multi-portfolio support – organise data into separate named files so multiple portfolios can be tracked independently.
   
*Main Features:*
   
| Feature                    | Description                                                                                 |
|----------------------------|---------------------------------------------------------------------------------------------|
| **ETF Management**         | Add and delete ETFs tracked in a portfolio file                                             |
| **Transaction Management** | Add, view, and delete individual buy/sell transactions                                      |
| **Excel Import**           | Upload an `.xlsx` / `.xls` file to bulk-import transactions                                 |
| **ETF Price Search**       | Look up the latest price and percentage changes (1D / 1M / 1Y) for any ETF symbol           |
| **Holdings Summary**       | Pie/bar chart showing the percentage distribution of ETF holdings                           |
| **Profit & Loss**          | Compute the current value of a savings plan based on past transactions and an interest rate |
| **File Management**        | Create and switch between multiple portfolio data files                                     |
   
Excel Import Format

Upload a spreadsheet with the following columns:

| Column | Description | Example                          |
|--------|-------------|----------------------------------|
| Type   | `Buy` or `Sell` | `Buy`                        |
| ETF    | ETF ticker symbol | `VWCE`                     |
| Units  | Number of units | `10`                         |
| Price  | Price per unit | `85.50`                       |
| Date   | Transaction date (`YYYY-MM-DD`) | `2024-01-15` |
   
*Technology Stack:*
   
- **Backend:**
  - ASP.NET Core 8 – REST API
  - C# / .NET 8
  - EPPlus – Excel file parsing
  - CsvHelper – CSV data handling
  - System.IO.Abstractions – testable file-system abstraction
  - Swashbuckle / Swagger – API documentation
  - MSTest – unit testing
   
- **Frontend:**
  - Angular 15 – SPA framework
  - Angular Material 15 – UI component library
  - Chart.js 4 – data visualisation (holdings charts)
  - TypeScript 4.9
  - Karma / Jasmine – unit testing
   
- **External Services:**
  - [EODHD API](https://eodhd.com/) – real-time and historical ETF price data (free tier supported)
     
**GarminAnalysis**
    
*Technology Stack:*
  
 - **Frontend:** 
 - **Backend:** 

## **Older projects:** ##

**chat-application**
