📈 Historical Stock Price Analysis for Top 10 Tech Companies

📌 Project Overview
This project provides a comprehensive analysis of the historical stock performance of 10 global tech giants (including Apple, Microsoft, Amazon, and Google) over the last decade. The goal was to visualize market volatility, compare growth trajectories, and identify long-term investment trends across the technology sector.

📊 Key Insights
Market Dominance: Amazon and Google consistently lead in total stock volume and closing value, representing the largest portion of the analyzed market share.

Price Volatility Trends: The "Average Daily Stock Price by Year" visual highlights a significant market correction period, allowing for a clear view of how these companies navigated global economic shifts.

Comparative Performance: While some companies show steady linear growth, others like Tesla exhibit high-reward volatility, as seen in the "Max vs Min Stock Price" analysis.

Volume Analysis: High trading volumes correlate strongly with major product launches and quarterly earnings reports for companies like Apple and Microsoft.

🛠️ Technical Toolkit
Data Visualization: Built an interactive, multi-page dashboard in Power BI using advanced slicers for year-over-year (YoY) filtering.

Data Modeling: Developed a robust data schema to handle millions of rows of historical price data (Open, High, Low, Close, and Volume).

DAX Formulas: Created custom measures for:

Average Daily Stock Volume

Total Opening vs. Total Closing Value

Price Spread (Max Price - Min Price)

UX/UI Design: Implemented a "Company Selector" grid to allow users to drill down into specific stock performance instantly.

📂 Repository Structure


├── .Report/                   # Power BI report metadata and visual layouts

├── .SemanticModel/            # Data model, relationships, and DAX measures

├── Stock_Data_Files/          # Historical CSV datasets for the 10 companies

├── Stock-Analysis-Final.pbip  # Main Power BI Project file

└── README.md                  # Project documentation


![Historical Stock Price Dashboard](screenshots/Historical Stock Price of 10 Popular Companies screenshot.png)
