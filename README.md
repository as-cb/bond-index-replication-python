# Dynamic Bond Index Replication 

**Replicating Bloomberg’s US Corporate Bond Index** using the TRACE transaction dataset.  
This project constructs investable portfolios of **50–100 bonds** out of ~**6,000** investable bonds using **XGBoost** and **Kalman Filters**, and evaluates out-of-sample tracking performance.

---

## Key Results

| Model          | OOS Tracking Error | OOS Benchmark Correlation |
|----------------|--------------------|---------------------------|
| **XGBoost**    | **2.01%**          | **0.808**                 |
| **Kalman Filter** | **2.60%**       | **0.935**                 |


---

## Data availability
**Large files are NOT uploaded to this GitHub repository** due to size limits. Download the datasets from the Google Drive links below and place them in the specified folders.

- Raw dataset (place under `raw_data/`):  
  - [`bond_returns.csv`](https://drive.google.com/file/d/1Vg1v80oxPq_id-rUcDeZNWcCHXkvk38z/view?usp=drive_link)

- Processed datasets (place under `processed_data/`):  
  - [`clean_bond_returns_long.csv`](https://drive.google.com/file/d/1syTvIfqM7zAsVRb3tkibje3kcpDX5kUe/view?usp=drive_link)  
  - [`processed_bond_returns.csv`](https://drive.google.com/file/d/1-_sCOfjwO8L4maoDBuyw92D5faEEXrFm/view?usp=drive_link)



