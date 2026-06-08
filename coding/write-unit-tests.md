# Write Unit Tests

**Category:** coding
**Model:** Any LLM
**Use case:** Generate comprehensive unit tests for a function or module

## Prompt

Write unit tests for the following code using [test framework]:

```
[Paste code here]
```

Cover:
1. Happy path / expected behavior
2. Edge cases (empty inputs, boundary values, null/undefined)
3. Error states and exceptions
4. Mock external dependencies where needed

Output tests in a runnable format with clear descriptions.

## Expected Output

A complete test file with descriptive test names, setup/teardown if needed, and mocks for external dependencies.

## Tips

- Specify your test framework (Jest, pytest, Mocha, Vitest)
- Mention coverage thresholds if you have targets
- Ask for mock examples if your code has API calls
