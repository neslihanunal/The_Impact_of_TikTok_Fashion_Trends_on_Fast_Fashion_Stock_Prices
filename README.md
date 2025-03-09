# The Impact of TikTok Fashion Trends on Fast Fashion Stock Prices

## Project Overview

I am Neslihan Ünal, a sophomore at Sabancı University majoring in Computer Science and Economics. This project is part of my DSA210 coursework, where I will explore the correlation between viral TikTok fashion trends and the stock performance of major fast fashion retailers like Inditex (Zara), H&M, and Shein.

Social media has become a driving force in consumer behavior, particularly within the fast fashion industry. This project aims to analyze whether viral TikTok fashion trends significantly impact stock prices, revenue spikes, and online interest in fast fashion brands. By leveraging data science techniques, I will investigate patterns in stock fluctuations around major viral trends.

---

## Objectives

1. **Identify the Relationship Between Social Media Trends and Stock Prices**  
   Investigate whether the popularity of specific fashion trends on TikTok correlates with fluctuations in stock prices of fast fashion brands.

2. **Analyze Market Reaction to Trend Peaks**  
   Determine whether stock prices experience noticeable changes following the peak popularity of a given fashion trend.

3. **Develop Data-Driven Insights**  
   Utilize statistical models to assess the significance of trend-based market reactions and provide insights for investors and fashion retailers.

4. **Apply Data Science Techniques**  
   Implement analytical methods to process large datasets, visualize trends, and evaluate relationships between social media engagement and financial performance.

---

## Motivation

Fast fashion brands rely heavily on consumer demand, which is increasingly influenced by digital platforms such as TikTok. Viral aesthetics like "coquette fashion," "Y2K style," or "quiet luxury" have gained significant traction, potentially impacting the sales and stock valuations of major retailers. Understanding this dynamic is crucial for investors, marketers, and businesses aiming to navigate the evolving fashion industry.

---

## Dataset

The dataset will be collected from two primary sources:

- **Stock Price Data**: Weekly historical stock prices of Inditex (Zara), H&M, and other relevant fast fashion brands retrieved from Yahoo Finance or Investing.com.
- **Google Trends Data**: Search volume and trend analysis of fashion-related keywords extracted via Google Trends API or manual tracking.

Each dataset will include:

1. **Date**: Timestamp for data alignment
2. **Stock Prices**: Open, close, high, low, and trading volume
3. **Trend Popularity**: Search frequency and engagement level of selected TikTok fashion trends

---

## Tools and Technologies

- **Python**: Data collection, analysis, and visualization
- **Pandas & NumPy**: Data manipulation
- **Matplotlib & Seaborn**: Data visualization
- **Yahoo Finance API**: Stock price retrieval
- **Google Trends API**: Trend popularity analysis
- **SciPy & Statsmodels**: Statistical correlation and regression analysis

---

## Analysis Plan

1. **Data Collection**  
   - Extract stock price data from Yahoo Finance or Investing.com.
   - Retrieve fashion trend search volume data using Google Trends API.

2. **Data Preprocessing**  
   - Clean and format data to ensure consistency.
   - Align trend peaks with stock price movements.

3. **Exploratory Data Analysis (EDA)**  
   - Visualize stock price trends and TikTok fashion trend peaks.
   - Identify possible correlations between stock price changes and viral trends.

4. **Hypothesis Testing**  
   - Null Hypothesis (H₀): TikTok fashion trends have no significant impact on fast fashion stock prices.
   - Alternative Hypothesis (H₁): TikTok fashion trends significantly influence fast fashion stock prices.

5. **Statistical & Regression Analysis**  
   - Conduct Pearson correlation tests to measure relationships.
   - Perform time-series regression analysis to predict stock movements based on trend data.

6. **Visualization & Insights**  
   - Generate time-series plots comparing trend peaks with stock price fluctuations.
   - Develop key insights based on statistical findings.

---

## Expected Outcomes

- Identification of whether stock prices show noticeable shifts following peak trend periods.
- Understanding of how different fashion trends impact individual brands.
- Insights into the role of social media in shaping financial market behavior.
- A data-driven approach for fashion retailers and investors to assess market sentiment.

---

## Limitations

- TikTok engagement metrics are not directly accessible, requiring reliance on Google Trends as a proxy.
- External market factors (e.g., inflation, earnings reports) may also influence stock prices, making trend-based attribution challenging.
- Limited dataset availability may impact long-term predictive accuracy.

---

## Future Work

- Expanding the dataset to include Instagram and Twitter trend data.
- Incorporating sentiment analysis from TikTok comments to gauge consumer interest more accurately.
- Exploring additional machine learning techniques for improved forecasting of stock price movements based on social trends.

---

## Disclaimer

This project is for academic and research purposes only. The analysis does not constitute financial advice or investment recommendations. While every effort is made to ensure data accuracy, market conditions and stock prices are influenced by numerous unpredictable factors beyond social media trends.
