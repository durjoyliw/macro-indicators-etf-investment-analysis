# Economic Indicators & ETF Performance Analysis: Investment Intelligence Dashboard

**Role:** Investment Analyst (Portfolio Strategy Team)  
**Business Context:** In volatile markets, understanding the relationship between macroeconomic indicators and ETF performance is critical for portfolio allocation decisions. This analysis provides real-time intelligence on how key economic signals (CPI, PMI, Fed Rate, Unemployment) correlate with major ETF movements to inform buy/sell timing and risk management strategies.

---

## Executive Summary

**Bottom Line:** This dashboard enables data-driven portfolio decisions by tracking the relationship between macroeconomic indicators and ETF performance, helping identify optimal entry/exit points and manage risk exposure during economic shifts.

**Key Value:** Monitor leading indicators like PMI and Fed Rate changes to anticipate ETF performance trends 30-90 days in advance, enabling proactive portfolio rebalancing rather than reactive adjustments.

<img width="900" alt="main-dashboard-overview" src="https://github.com/kantrishav/Power-BI-Dashboard-For-Economic-Indicators-vs-ETFs-and-Stock/assets/28995985/bb06b27f-b0e4-4f35-857a-a5277282cb7b">

---

## Critical Market Insights

### 🎯 Macroeconomic Impact on ETF Performance

#### **1. Federal Reserve Rate Decisions**
- **Investment Signal:** Track Fed Rate movements to anticipate growth vs. value stock rotation
- **Portfolio Impact:** Rising rates typically pressure high-growth ETFs (ARKK) while stabilizing dividend-focused funds
- **Action Point:** Adjust tech-heavy allocations 2-3 months before anticipated rate changes

#### **2. Inflation Indicators (CPI)**
- **Investment Signal:** CPI acceleration above 3% historically correlates with increased market volatility
- **Portfolio Impact:** High inflation periods favor commodity and value ETFs over growth funds
- **Action Point:** Increase defensive positions when CPI shows sustained upward trends

#### **3. Manufacturing Activity (PMI)**
- **Investment Signal:** PMI below 50 signals contraction; above 55 indicates expansion
- **Portfolio Impact:** Strong PMI readings support cyclical and industrial sector ETFs
- **Action Point:** PMI is a leading indicator—use for early positioning in economic cycle transitions

#### **4. Employment Trends (Unemployment Rate)**
- **Investment Signal:** Rising unemployment typically precedes market corrections by 3-6 months
- **Portfolio Impact:** Deteriorating employment trends warrant defensive positioning and increased cash reserves
- **Action Point:** Monitor initial jobless claims for early warning signals

---

## Investment Decision Framework

### Tracked ETFs & Strategic Positioning

**QQQ (Invesco QQQ Trust) - Tech-Heavy Growth**
- **Correlation:** Inverse relationship with Fed Rate increases
- **Use Case:** Aggressive growth allocation during low-rate environments
- **Risk Factor:** High sensitivity to inflation and rate hikes

**ARKK (ARK Innovation ETF) - Disruptive Innovation**
- **Correlation:** Highly sensitive to Fed Rate and inflation expectations
- **Use Case:** Speculative allocation for high-risk tolerance portfolios
- **Risk Factor:** Extreme volatility during monetary policy shifts

**SPY (SPDR S&P 500 ETF) - Broad Market Benchmark**
- **Correlation:** Moderate sensitivity to all macro indicators
- **Use Case:** Core portfolio holding and risk benchmark
- **Risk Factor:** Most reliable indicator of overall market sentiment

<img width="900" alt="etf-performance-analysis" src="https://github.com/kantrishav/Power-BI-Dashboard-For-Economic-Indicators-vs-ETFs-and-Stock/assets/28995985/64ce7a0d-3e5f-4683-bc27-a33a480d4858">

---

## Dashboard Capabilities for Investment Teams

### **Real-Time Market Intelligence**

**1. Economic Cycle Positioning**
- Identify current phase of economic cycle (expansion, peak, contraction, trough)
- Correlate macro indicators with historical ETF performance patterns
- Generate timing signals for sector rotation strategies

**2. Risk Management Indicators**
- Monitor divergence between economic indicators and ETF valuations
- Track volatility patterns during periods of macro uncertainty
- Identify overextended positions requiring rebalancing

**3. Comparative Performance Analysis**
- Benchmark individual ETF performance against economic backdrop
- Analyze historical correlations to predict future movements
- Identify outliers and arbitrage opportunities

**4. Trend Forecasting & Scenario Planning**
- Leverage predictive analytics to model "what-if" economic scenarios
- Project ETF performance under different Fed Rate paths
- Stress-test portfolio allocations against macro headwinds

<img width="900" alt="trend-analysis-forecasting" src="https://github.com/kantrishav/Power-BI-Dashboard-For-Economic-Indicators-vs-ETFs-and-Stock/assets/28995985/78aa8903-31b5-4e3a-a102-fa1033544fd2">

---

## Recommended Use Cases for Investment Professionals

### **Portfolio Managers**
- **Morning Briefings:** Review overnight macro developments and their ETF impact
- **Rebalancing Decisions:** Use correlation analysis to time portfolio adjustments
- **Client Reporting:** Explain market movements through economic context

### **Risk Analysts**
- **Exposure Monitoring:** Track macro risk factors affecting current holdings
- **Stress Testing:** Model portfolio behavior under adverse economic scenarios
- **Early Warning System:** Identify deteriorating economic indicators before market repricing

### **Investment Strategists**
- **Tactical Allocation:** Adjust sector/factor exposure based on economic phase
- **Thematic Research:** Identify structural trends in macro-ETF relationships
- **Market Commentary:** Generate data-backed investment narratives for clients

---

## Key Economic Indicators Monitored

### **Consumer Price Index (CPI)**
- **What It Tells Us:** Inflation rate and purchasing power trends
- **Investment Relevance:** High inflation erodes growth stock valuations
- **Update Frequency:** Monthly (BLS release)

### **Purchasing Managers Index (PMI)**
- **What It Tells Us:** Manufacturing sector health and economic momentum
- **Investment Relevance:** Leading indicator for economic expansion/contraction
- **Update Frequency:** Monthly (ISM release)

### **Federal Reserve Rate**
- **What It Tells Us:** Cost of capital and monetary policy stance
- **Investment Relevance:** Primary driver of equity valuations and sector rotation
- **Update Frequency:** Eight FOMC meetings annually

### **Unemployment Rate**
- **What It Tells Us:** Labor market health and consumer spending capacity
- **Investment Relevance:** Lagging indicator but critical for economic cycle identification
- **Update Frequency:** Monthly (BLS release)

---

## Analytical Advantages

### **Why This Approach Works**

**1. Leading vs. Lagging Indicators**
- Combines forward-looking indicators (PMI) with current conditions (CPI)
- Enables proactive positioning rather than reactive trading

**2. Multi-Factor Analysis**
- No single indicator drives markets—this dashboard shows the complete picture
- Identify regime changes when multiple indicators shift simultaneously

**3. Historical Context**
- Compare current readings to historical ranges and inflection points
- Learn from past market reactions to similar economic conditions

**4. Customizable Views**
- Filter by timeframe (daily, weekly, monthly, quarterly)
- Isolate specific indicator-ETF relationships for deep-dive analysis
- Export data for integration with portfolio management systems

---

## Next Steps for Enhanced Analysis

To further strengthen investment decision-making, consider expanding to:

1. **Sector-Level Analysis:** Track economic indicators against individual S&P 500 sectors
2. **International Correlations:** Add global economic indicators (ECB rates, China PMI)
3. **Alternative Data Integration:** Incorporate sentiment analysis, options flow, institutional positioning
4. **Quantitative Signals:** Build algorithmic trading rules based on indicator thresholds
5. **Risk Parity Models:** Optimize portfolio weights based on macro volatility regimes

---

## Technical Implementation

**Platform:** Microsoft Power BI  
**Data Sources:** Federal Reserve Economic Data (FRED), Yahoo Finance API, Bureau of Labor Statistics  
**Update Frequency:** Real-time for ETF prices, periodic for economic indicators (as released)  
**Refresh Schedule:** Automated daily refresh at market close

### **Dashboard Features**

**Interactive Filtering:**
- Date range selection for historical analysis
- Multi-ETF comparison views
- Economic indicator overlays and correlations

**Visualization Types:**
- Time-series line charts for trend identification
- Correlation heatmaps for relationship analysis
- Candlestick charts for detailed ETF price action
- Economic indicator gauges with historical context

**Alert Capabilities:**
- Threshold-based notifications for significant economic releases
- Divergence alerts when ETF performance deviates from historical patterns
- Volatility spike warnings during macro uncertainty

---

## About This Project

This dashboard transforms raw economic data into actionable investment intelligence. Rather than simply displaying numbers, it reveals the *relationships* between macroeconomic conditions and market performance—enabling investors to position portfolios ahead of market movements rather than reacting after they occur.

**Investment Philosophy:** Markets are forward-looking and respond to changing economic conditions before they fully materialize. By monitoring the right indicators and understanding their historical relationships with asset prices, investors can make more informed, timely decisions that enhance risk-adjusted returns.

**Target Users:** Portfolio managers, investment analysts, risk managers, financial advisors, and individual investors seeking systematic, data-driven approaches to market timing and asset allocation.

---

