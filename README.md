# Web Programming Course Project
# BDT Currency Converter

# BDT Currency Converter

## Project Sponsor
Bangladesh Bank(Assume)

## Business Need
To support individuals, businesses, and investors in making informed financial decisions, there is a critical need for a reliable and accessible platform that provides up-to-date conversion rates of Bangladeshi Taka (BDT) against major foreign currencies and precious metals. This tool will help users track real-time and historical price trends, enabling better planning for travel, trade, remittances, and investments.

## Business Requirement

1.  **Currency Conversion Feature**
    *   Convert Bangladeshi Taka (BDT) to popular foreign currencies (e.g., USD, EUR, GBP, INR, etc.)
    *   Real-time exchange rates via an API (e.g., Exchange Rate-API, Forex API)

2.  **Precious Metal Conversion Feature**
    *   Convert BDT to precious metals (Gold, Silver) by gram
    *   Live price fetching for gold and silver (via metal pricing API)

3.  **Graphical Price Representation**
    *   Display historical exchange rates and metal prices using interactive line or bar graphs

4.  **Filter Options for Graphs**
    *   Show conversion trends for:
        *   Last week
        *   Last month
        *   Last 3 months
        *   Custom date range (optional)

5.  **User Interface (UI) Requirements**
    *   Clean and responsive UI
    *   Easy selection between currencies or metals
    *   Toggle for changing BDT to target unit and vice versa

6.  **Backend Functionality**
    *   Fetch and cache real-time data to optimize performance
    *   Historical data processing and storage

7.  **Error Handling and Fallbacks**
    *   Handle API failures or rate limit issues gracefully
    *   Display fallback message or cached values when needed

## Business Value

1.  **Financial Transparency**
    *   Helps users understand the real-time value of BDT in foreign markets and commodity terms

2.  **Investor & Traveler Utility**
    *   Useful for people investing in precious metals or traveling abroad

3.  **Educational Purpose**
    *   Visual data helps educate users about currency/metal price trends and fluctuations

4.  **Market Awareness**
    *   Supports better financial decision-making based on historical trends

5.  **Competitive Advantage**
    *   Combines both currency and precious metal conversion in one app, which is uncommon in local solutions

6.  **Localization**
    *   Tailored specifically for Bangladeshi users, fulfilling a niche demand

## Special Issues

*   **API Reliability** – Dependence on third-party APIs may cause downtime or data inaccuracies.
*   **Security Risks** – Sensitive data and API keys must be protected from breaches or misuse.
*   **Political & Economic Instability** – Sudden market changes may affect currency and metal price accuracy.
*   **Performance Challenges** – Heavy data or graph processing can slow down the app.
*   **Device Compatibility** – UI and performance must be optimized for mobile, tablet, and desktop.
*   **Network Latency** – Slow or unstable connections may delay real-time data fetching.
*   **Regulatory Compliance** – Legal and licensing requirements must be followed for financial data.
*   **User Trust & Transparency** – Clear data sources and update times are needed to maintain credibility.
