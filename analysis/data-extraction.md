# Data Extraction

**Category:** analysis
**Model:** GPT-4 / Claude
**Use case:** Extract structured data from unstructured text (receipts, invoices, emails, etc.)

## Prompt

Extract structured data from the following text:

```
[Paste text to extract from]
```

Schema (extract all that apply):
- Date(s)
- Names (people, companies, places)
- Monetary amounts (with currency)
- Email addresses
- Phone numbers
- Addresses
- URLs
- Key metrics or numbers
- Action items

Output as JSON with null for missing fields.

## Expected Output

A clean JSON object with all extracted fields, null for missing values.

## Tips

- Provide a clear example of the output format you want
- Specify date format (ISO 8601, etc.)
- Mention if you need nested or flat structure
- For invoices, provide sample expected fields in advance
