# Refactor Legacy Code

**Category:** coding
**Model:** Claude / GPT-4
**Use case:** Modernize old code without changing behavior

## Prompt

Refactor this legacy code to modern standards:

```
[Paste legacy code here]
```

Requirements:
- Keep the same external behavior (don't change inputs/outputs/API)
- Use modern syntax and best practices
- Add type hints / types
- Split into smaller functions if needed
- Add docstrings
- Improve variable naming
- Add error handling

Explain each change you make and why.

## Expected Output

Before/after code comparison with explanations for each refactoring decision.

## Tips

- Specify the target language version (e.g., ES2022, Python 3.12)
- Mention your style guide if applicable (Airbnb, Google, etc.)
- Request a diff format for easy review
