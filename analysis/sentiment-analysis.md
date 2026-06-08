# Sentiment Analysis

**Category:** analysis
**Model:** Any LLM
**Use case:** Analyze the sentiment, tone, and emotional subtext of a text

## Prompt

Analyze the sentiment of the following text. Provide:

1. Overall sentiment: positive / negative / neutral / mixed
2. Sentiment score: -1.0 to 1.0
3. Key emotional tones detected (frustration, excitement, disappointment, etc.)
4. Specific phrases that indicate the sentiment
5. Confidence level (low / medium / high)

Text:
```
[Paste text here]
```

## Expected Output

Structured analysis with score, emotions, evidence phrases, and confidence level.

## Tips

- Specify if you want analysis on a sentence-by-sentence level
- Mention the domain (reviews, social media, support tickets) for context
- Ask for emoji or label output if integrating with a pipeline
