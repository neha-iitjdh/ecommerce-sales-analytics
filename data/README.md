# Data Directory

## Structure
- `raw/`: Original, unprocessed datasets
- `processed/`: Cleaned and feature-engineered datasets

## Datasets

### ecommerce_data.csv
- **Source**: Generated using Faker library
- **Records**: 10,000 transactions
- **Date Range**: Last 2 years
- **Columns**: order_id, customer_id, order_date, category, product_name, price, quantity, total_amount, customer_city, customer_state

### ecommerce_data_processed.csv
- **Source**: Processed from raw data
- **Additional Features**: year, month, day_of_week
- **Transformations**: Date parsing, feature engineering

## Data Generation Logic
The synthetic data mimics realistic e-commerce patterns:
- 5 product categories with appropriate price ranges
- Seasonal variations in order volume
- Realistic customer distribution
- Quantity distributions based on typical purchase behavior

*Note: All data is synthetic and generated for learning purposes.*