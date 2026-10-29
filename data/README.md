# Data

The dataset is a teaching dataset provided by the University of Greenwich for the module Advanced Analytics: Statistics and Machine Learning (COMP1942). It is **not redistributed** in this repository.

## Expected File

Place the file at `data/Dataset.xlsx` (first sheet, header in row 1). The notebook reads it with `pd.read_excel("../data/Dataset.xlsx")`.

## Expected Columns

1,500 rows, 17 columns, no missing values.

| Column | Type | Used in the analysis |
|---|---|---|
| `product_id` | int64 | |
| `units_sold_first_30d` | int64 | |
| `launch_discount_pct` | float64 | predictor |
| `ad_spend_usd` | int64 | predictor |
| `store_region_index` | int64 | |
| `product_price_usd` | float64 | |
| `shelf_space_sqft` | float64 | |
| `brand_familiarity_score` | float64 | predictor |
| `social_media_mentions` | int64 | predictor |
| `product_category_index` | int64 | |
| `competitor_count_nearby` | int64 | |
| `weekday_launch_flag` | int64 | |
| `season_index` | int64 | |
| `internal_reference_code` | int64 | |
| `revenue_first_30d_usd` | float64 | |
| `success_probability` | float64 | dependent variable |
| `is_successful` | int64 | |

All 17 numeric columns are included in the MinMax-scaled histogram grid. The executed notebook outputs are kept so the results can be read without the data.
