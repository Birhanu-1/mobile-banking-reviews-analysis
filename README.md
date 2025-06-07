# mobile-banking-reviews-analysis
## Methodology

### Data Collection
- Used `google-play-scraper` to fetch 400+ reviews for each app:
  - Commercial Bank of Ethiopia (CBE)
  - Bank of Abyssinia (BOA)
  - Dashen Bank

### Preprocessing
- Removed duplicates and missing entries
- Normalized date format to YYYY-MM-DD
- Stored cleaned data in `clean_reviews.csv` with columns:
  `review`, `rating`, `date`, `bank`, `source`

### Tools
- Python
- Pandas
- GitHub
