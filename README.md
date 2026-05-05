# Email Data Extractor

Extract financial data from emails using Regex pattern matching.

## Features
- Extract sender, date, amount, subject
- Auto-categorize (Invoice, Receipt, Subscription)
- Confidence scoring (0-100%)
- Batch processing (100+ emails)
- CSV/JSON export

## Quick Start
```python
from extract import EmailExtractor
extractor = EmailExtractor()
results = extractor.process_batch(emails)
df = pd.DataFrame(results)
df.to_csv('output.csv', index=False)
```

## Output
