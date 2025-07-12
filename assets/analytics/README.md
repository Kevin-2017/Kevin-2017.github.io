# Monthly Analytics Data

This folder contains automatically generated monthly page view analytics for kevin-ai.com.

## File Format

Each monthly file follows the pattern: `monthly-YYYY-MM.json`

### Data Structure

```json
{
  "month": "2025-01",
  "views": 1250,
  "uniqueVisitors": ["visitor_123...", "visitor_456..."],
  "lastSaved": "2025-01-31T23:59:59.999Z",
  "domain": "kevin-ai.com"
}
```

## Automatic Generation

- Data is collected via Google Analytics and local tracking
- Files are automatically generated at the end of each month
- Data includes total page views and unique visitor tracking
- All data is anonymized and privacy-compliant

## Manual Data Addition

To manually add a monthly analytics file:

1. Create a new JSON file following the naming convention
2. Include all required fields in the data structure
3. Commit the file to this directory

The page view counter will automatically load and display this data. 