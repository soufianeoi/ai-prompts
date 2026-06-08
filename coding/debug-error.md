# Debug an Error

**Category:** coding
**Model:** Any LLM
**Use case:** Find and fix a bug from an error message or stack trace

## Prompt

I'm getting this error in my [language/framework] application:

[Paste error message / stack trace here]

Code context:

```
[Paste relevant code here]
```

What's causing this error and how do I fix it? Consider:
1. Root cause analysis
2. Minimal fix
3. Prevention for the future

## Expected Output

A clear explanation of the root cause, a code fix, and steps to prevent recurrence.

## Tips

- Include the full stack trace, not just the last line
- Specify exact package versions
- Mention what you already tried
