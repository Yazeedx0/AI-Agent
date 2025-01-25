# AI-Powered Product Research and Comparison System

An intelligent system leveraging multiple AI agents to automate product research, analysis, and recommendation, enabling data-driven purchasing decisions. This project is designed to help users find the best products at the most competitive prices by automating the entire process of searching, comparing, and extracting product details.

## Table of Contents
- [Project Overview](#project-overview)
- [Key Features](#key-features)
- [Agents](#agents)
- [Workflow](#workflow)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Example](#example)
- [License](#license)

---

## Project Overview
This system employs collaborative AI agents to streamline product discovery and evaluation. It automates data collection, comparative analysis, and generates actionable reports for users. The project is built using Python and integrates with various APIs and tools to ensure efficient and accurate results.

## Key Features
- **Automated Research**: Web scraping and API integration with e-commerce platforms.
- **NLP-Powered Insights**: Sentiment analysis of product reviews.
- **Dynamic Search**: Generates optimized search queries for product discovery.
- **Comparative Analytics**: ML-driven product scoring (price/quality/reliability).
- **Collaborative AI**: Agents work in tandem for optimized results.

---

## Agents
1. **Search Queries Recommendation Agent**  
   - Generates optimized search queries for product discovery.
   - Ensures queries lead to e-commerce product pages.

2. **Search Engine Agent**  
   - Searches for products based on the suggested queries.
   - Filters out suspicious links and low-confidence results.

3. **Web Scraping Agent**  
   - Extracts product details from e-commerce store pages.
   - Collects data such as product title, price, discounts, and specifications.

---

## Workflow
1. **Input Criteria**: Define product specs (e.g., product name, websites, country, language).
2. **Query Generation**: Search Queries Recommendation Agent generates optimized search queries.
3. **Data Collection**: Search Engine Agent collects product data from specified websites.
4. **Data Extraction**: Web Scraping Agent extracts detailed product information.
5. **Reporting**: Outputs a JSON file with detailed product recommendations.

---

## Technologies
- **AI Frameworks**:  
  - OpenAI GPT-4 (for query generation and analysis)
  - CrewAI (for agent coordination)
  - AgentOps (for agent monitoring)
- **APIs**:  
  - Tavily API (for search functionality)
  - ScrapeGraph API (for web scraping)
- **Libraries**:  
  - Python (requests, pandas, numpy, BeautifulSoup, Scrapy)
  - Pydantic (for data validation)

---

## Installation
### Prerequisites
- Python 3.8+
- API keys (OpenAI, Tavily, ScrapeGraph, AgentOps)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/Yazeedx0/AI-Agent.git
   cd AI-Agent
