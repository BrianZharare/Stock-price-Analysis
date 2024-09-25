# **Title:** Exploring the Relationship Between S&P 500 and VIX; A Descriptive Analysis of Stock Market Volatility

## *Introduction*

The recent historic lows in the CBOE Volatility Index (VIX) in June, reaching 11.94 on June 13th, have sparked concerns among stakeholders about the potential for a significant market downturn. Various financial publications have suggested that this decreased volatility may indicate investor complacency, prompting worries about the risks of staying invested in stocks. The S&P 500 index (GSPC), a widely followed benchmark, is often cited as a key influencer of VIX fluctuations. This raises important questions: Is the anticipated VIX spike supported by empirical evidence, or is it merely speculative? Does the relationship between S&P 500 and VIX warrant caution, or are stakeholders overreacting? This project seeks to provide a descriptive analysis of the S&P 500 and VIX, exploring their historical dynamics and shedding light on the validity of these concerns.

## *Methodology*

This project employed the Ask, Prepare, Process, Analyze, Share (APPS) framework.

### **1. Ask**

The research questions guiding this study were:

- What is the relationship between the S&P 500 and VIX?
- How rare are VIX readings below 12?

### **2. Prepare**

To address these questions, the following steps were taken:

*Data Acquisition*: Dates, closing prices for S&P 500, and closing VIX readings were obtained from Yahoo Finance.

*Time Frame*: Data spanning January 2020 to June 2024 was deemed sufficient for analysis.


*Tools*: R programming language was used for data extraction, while Excel facilitated data design, cleaning, auditing, analysis, and visualization.

### **3. Process**

*Data Extraction*: Data was retrieved from Yahoo Finance.

*Data Cleaning*: Raw data in CSV format was cleaned by removing rows with NA values due to public holidays.


*Data Design*: Data was organized for analysis.

*Data Audit*: Pivot tables ensured data integrity, verifying years, months, and trading days.


### **4. Analysis**

Key findings:

- *Mean VIX*: 21.88, indicating that readings below 12 are rare.
- *Median VIX*: 20.34, less influenced by extreme values.
- *Mode VIX*: 12.85, the most frequent reading.
- *Max/Min VIX*: 82.69 and 8.86, respectively.

*Correlation Analysis (2023)*

*Correlation Coefficient*: -0.88, indicating a strong negative relationship between VIX and S&P 500.

### **5. Share**

Results were presented using visualizations to facilitate understanding.

#### *Correlation*
1. Excel
- A combo chart with two Y-axes effectively illustrated the correlation between VIX and S&P 500 for 2023.
- Negative values were highlighted in red for enhanced visualization.

2.Python

Utilizing the ffn library, we visualized the relationship between the S&P 500 (SP500) and the CBOE Volatility Index (VIX) through a heatmap. The correlation coefficient of -0.7 over the entire dataset indicates a strong negative correlation, substantiating the notion that these two variables are inversely related.

#### *Performance Evaluation*

The performance plot, generated using ffn, effectively communicates the growth trajectory of the investment portfolio’s value over time. Notably, the SP500 exhibits steady growth despite fluctuations in the VIX over the years, underscoring its resilience.

#### *Drawdown Analysis*

Drawdowns are a critical risk management metric, representing the peak-to-trough decline in investment value. The ffn library facilitates the visualization of drawdown plots. Our analysis reveals intriguing insights:

- A decline in VIX tends to coincide with a peak in SP500, and vice versa.
- Currently, the SP500 is at its peak, suggesting potential vulnerability to a rise in VIX, which may lead to a decline in SP500.



# **Recommendations and Conclusion**

Based on our descriptive analysis of the relationship between the S&P 500 and VIX, we recommend the following:

*Investment Strategies:*

1. *Diversification*: Allocate assets to minimize exposure to VIX-induced volatility.
2. *Risk Management*: Implement hedging strategies to mitigate potential losses.
3. *Market Timing*: Monitor VIX movements to inform SP500 investment decisions.

*Key Takeaways:*

1. The strong negative correlation between SP500 and VIX indicates an inverse relationship.
2. VIX readings below 12 are rare, with a mean VIX of 21.88.
3. SP500 exhibits steady growth despite VIX fluctuations.
4. Drawdown analysis suggests potential vulnerability in SP500 due to rising VIX.

*Conclusion:*

Our analysis provides empirical evidence supporting concerns about the potential for a significant market downturn. The rare occurrence of VIX readings below 12 and the strong negative correlation with SP500 warrant caution. Investors should consider diversification, risk management, and market timing strategies to mitigate potential losses.

By examining the correlation, performance, and drawdown dynamics between SP500 and VIX, investors can refine their portfolio optimization and risk management approaches.

