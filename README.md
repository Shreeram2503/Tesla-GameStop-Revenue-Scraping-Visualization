# Tesla-GameStop-Revenue-Scraping-Visualization
Web scraping and financial data visualization of Tesla &amp; GameStop quarterly revenue using BeautifulSoup, Pandas, and Matplotlib. Comparative time-series analysis and clean storytelling visuals included.


# Tesla & GameStop Revenue Scraping & Visualization  
**Web Scraping, Data Cleaning & Financial Visualization using Python**

## 📁 Project Overview  
This project performs web scraping and time-series visualization for quarterly revenue data of **Tesla (TSLA)** and **GameStop (GME)**. By extracting structured tables from an HTML source and applying data wrangling techniques in Python, it highlights trends and volatility in the financial trajectories of both companies.

## 🌐 Web Data Extraction  
- **Source**: HTML page containing revenue tables  
- **Tools Used**: BeautifulSoup for parsing and Pandas for transformation  
- **Target Columns**: Quarter, Revenue (in USD) for Tesla and GameStop  
- **Result**: Two cleaned DataFrames ready for time-series plotting and analysis

## 🧼 Data Cleaning  
- ✅ Handled `$` and `,` with regex (`r"\$|,"`) in Pandas  
- ✅ Converted revenue strings to integers  
- ✅ Formatted quarters using Pandas datetime  
- ✅ Validated row consistency across both tables

## 📊 Visualization & Insights  
- 📈 Line plots showing Tesla vs GameStop revenue growth  
- 📊 Bar graphs comparing recent quarters  
- 🔍 Key Insight: Tesla shows a consistent upward trend; GameStop’s revenue remains relatively flat with slight variations  
- 💬 Potential impact of market perception and external events (e.g., meme stock rallies)

## ⚙️ Tech Stack  
- Python  
- BeautifulSoup  
- Pandas  
- Matplotlib  
- Jupyter Notebook

## 🚀 Outcomes  
- Mastered web scraping from financial HTML content  
- Demonstrated comparative analysis using time-series plots  
- Strengthened understanding of regex cleaning and date formatting  
- Created intuitive visuals highlighting company revenue trends

## 📝 Author  
**T Shreeram Rohit**  
LinkedIn: [tshreeramrohit](https://linkedin.com/in/tshreeramrohit)  
GitHub: [Shreeram2503](https://github.com/Shreeram2503)
