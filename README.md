# Product Combination Generator

This project allows users to upload a product list and receive combinations (product sets) whose total prices fall within a specified range.

---

## 🔧 Features

- Upload a file with product IDs and their prices
- Set a lower and upper limit for the target price range
- Automatically generate all valid product combinations
- Enter an email ID to receive the results (if configured)

---

## 📥 Input

- A `.csv` or `.xlsx` file with columns:
  - **Pid**: Product ID (e.g., P1, P2, ...)
  - **Price**: Price of each product

### Example:

| Pid | Price |
|-----|-------|
| P1  | 64    |
| P2  | 88    |
| P3  | 152   |
| P4  | 93    |
| P5  | 76    |

---

## 📤 Output

The app will return all **product combinations** where the **sum of prices** falls within the given limits.

### Example Output (for 490–510):

