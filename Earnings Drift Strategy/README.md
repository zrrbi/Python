# **Earnings Momentum and Quality Strategy (EMQ)**

This folder contains the code and analysis for our **Earnings Momentum and Quality Strategy (EMQ)**, developed as part of the **Quantitative Portfolio Management** course at **Chicago Booth**, under Professors **Ralph S.J. Koijen** and TA **Federico Mainardi**.

## **Project Overview**

This project explores the idea that market participants are slow to react to new earnings data, creating temporary mispricing of stocks. By leveraging behavioral biases such as the disposition effect and post-earnings drift, we designed a **long-short equity strategy** that generates alpha through:

1. **Going long** on stocks that strongly beat earnings expectations.
2. **Shorting** stocks that significantly miss earnings expectations.
3. **Filtering** stocks using quality metrics like the Beneish M-Score and Altman Z-Score to ensure portfolio robustness.

## **Key Features**

### **Economic Rationale**
- Behavioral biases lead to underreaction to earnings surprises, resulting in exploitable price drifts.
- Investors tend to:
  - Prematurely sell stocks after positive surprises.
  - Hold losing stocks after negative surprises.

### **Investment Strategy**
- **Long positions**: Stocks with significant earnings beats (10-15% above consensus).
- **Short positions**: Stocks with significant earnings misses (10-15% below consensus).

### **Applied Quality Factors**
- **Beneish M-Score**: Detects potential earnings manipulation to filter out low-quality earnings.
- **Altman Z-Score**: Assesses insolvency risk for robust short-side selection.

### **Backtesting Results**
- The strategy demonstrated consistent alpha generation over the test period, significantly outperforming benchmark indices.

## **Team Members**

This project was a collaborative effort by:
- **Katie Fechner**
- **Nathan Frost**
- **Justin Steuer**
- **Lauren Zheng**
