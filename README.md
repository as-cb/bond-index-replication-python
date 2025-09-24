# Dynamic Bond Index Replication 

**Replicating Bloomberg’s US Corporate Bond Index** using the TRACE transaction dataset.  
This project constructs investable portfolios of **50–100 bonds** out of ~**6,000** investable bonds using **XGBoost** and **Kalman Filters**, and evaluates out-of-sample tracking performance.

---

## Key results
- **XGBoost**: Out-of-sample (OOS) tracking error = **2.01%** // OOS benchmark correlation = **0.808**  
- **Kalman Filter**: Out-of-sample (OOS) tracking error = **2.60%** // OOS benchmark correlation = **0.935**

---

## Data availability
**Large files are NOT uploaded to this GitHub repository** due to size limits. Download the datasets from the Google Drive links below and place them in the specified folders.

- Raw dataset (place under `raw_data/`):  
  - `bond_returns.csv` — **Google Drive:** `<GOOGLE_DRIVE_LINK_BOND_RETURNS>`

- Processed datasets (place under `processed_data/`):  
  - `clean_bond_returns_long.csv` — **Google Drive:** `<GOOGLE_DRIVE_LINK_CLEAN_BOND_RETURNS_LONG>`  
  - `processed_bond_returns.csv` — **Google Drive:** `<GOOGLE_DRIVE_LINK_PROCESSED_BOND_RETURNS>`


