# Chicago Traffic Crashes ETL Pipeline

## Milestone 1: Data Collection & Preprocessing

**Dataset**: Chicago Traffic Crashes (1.067 million rows)

### Files
- `chicago_traffic_crashes_etl.ipynb` → Main notebook
- `data/chicago_traffic_crashes_cleaned.parquet` → Cleaned & optimized data (recommended to use)

### How to Use

```python
import polars as pl

# Load the cleaned data
df = pl.read_parquet("data/chicago_traffic_crashes_cleaned.parquet")
print(df.shape)
