# Code Review

**Category:** coding
**Model:** Claude / GPT-4
**Use case:** Get a thorough code review on a pull request or code snippet

## Prompt

Review this code as if you're a senior engineer on my team. Be thorough but constructive.

```
[Paste code here]
```

Focus on:
1. Bugs and logic errors
2. Security vulnerabilities
3. Performance issues
4. Code style and maintainability
5. Missing edge cases or error handling
6. Suggestions for improvement (with code examples)

Rate it: Good / Needs fixes / Must rewrite

## Expected Output

A structured review with severity ratings for each issue, code examples for fixes, and an overall rating.

## Tips

- Specify the language and framework version
- Include the full file if possible
- Ask for a specific checklist (security, performance, etc.)
