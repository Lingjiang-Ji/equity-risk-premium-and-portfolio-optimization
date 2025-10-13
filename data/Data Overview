## 📂 Data Overview

The dataset used in this project is stored in the `data/` directory.  
It consolidates multiple sources commonly used in empirical asset pricing research,  
providing a long-term monthly panel of U.S. market and macroeconomic variables.

### Dataset: `us_equity_factors_1963_2025.xlsx`

| Sheet | Description | Source |
|--------|--------------|--------|
| **Data** | Main working sheet — integrates equity, bond, and gold returns. Used for ERP computation. | Compiled from CRSP, FRED, and Kenneth R. French Data Library |
| **GW** | Goyal & Welch (2008) predictive variables — dividend-price ratio, interest rates, inflation. | Goyal & Welch Dataset |
| **CRSP** | Historical market-level returns (value-weighted, equal-weighted), T-bill and bond yields. | CRSP Database |
| **GOLD** | Monthly gold prices and returns. | Yahoo Finance |
| **BTC-USD** | Monthly Bitcoin returns (2014–present). | Yahoo Finance |
| **FF-12Ind** | Fama-French 12 Industry Portfolios. | Kenneth R. French Data Library |
| **FF-3Factor** | Fama-French 3-Factor Model (MKT, SMB, HML, RF). | Kenneth R. French Data Library |

### Notes
- The **`Data`** sheet is the primary dataset used for ERP estimation throughout this project.  
- **Risk-free rate** is derived from the 3-month Treasury Bill series (`3m` column).  
- **Equity returns** (`vwret`) represent value-weighted stock market performance.  
- Macroeconomic predictors (`dp`, `10y`, etc.) are used for forward-looking ERP models.  
- All returns are expressed in decimal form (e.g., 0.01 = 1%).

---

📘 *For detailed variable definitions and data construction notes, see the file:*  
`data/us_equity_factors_1963_2025说明.docx`
