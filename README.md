# Medicare & Medicaid Spending by Drug (2020–2024)

Shared data for our R class group project comparing Medicare Part D and Medicaid drug spending.

## Files

| File | What it is | Original CMS file name |
|---|---|---|
| `Medicare_Part_D_Spending_by_Drug_2024.csv` | Medicare Part D spending by drug, 2020–2024 | `DSD_PTD_RY26_P04_V10_DY24_BGM.csv` |
| `Medicaid_Spending_by_Drug_2024.csv` | Medicaid spending by drug, 2020–2024 | `DSD_MCD_RY26_P06_V20_D24_BGM.csv` |

Both files contain the same data as the CMS release; only the file names were changed.

## Sources

- Medicare Part D Spending by Drug: https://data.cms.gov/summary-statistics-on-use-and-payments/medicare-medicaid-spending-by-drug/medicare-part-d-spending-by-drug
- Medicaid Spending by Drug: https://data.cms.gov/summary-statistics-on-use-and-payments/medicare-medicaid-spending-by-drug/medicaid-spending-by-drug

Both are public data from the Centers for Medicare & Medicaid Services (CMS), 2024 data release.

## Reading the data in R

Click a file above, then **Raw**, and use that address in `read_csv()`:

```r
library(tidyverse)

Medicare_Part_D_Spending_by_Drug_2024 <- read_csv("RAW-LINK-TO-MEDICARE-FILE")
DSD_MCD_RY26_P06_V20_D24_BGM <- read_csv("RAW-LINK-TO-MEDICAID-FILE")
```
