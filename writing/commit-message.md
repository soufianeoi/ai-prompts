# Write a Git Commit Message

**Category:** writing
**Model:** Any LLM
**Use case:** Craft clear, conventional commit messages

## Prompt

Generate a git commit message for these changes:

```
[Paste git diff or description of changes]
```

Follow [Conventional Commits](https://www.conventionalcommits.org/) format:
- `feat:` for new features
- `fix:` for bug fixes
- `docs:` for documentation
- `refactor:` for code restructuring
- `test:` for tests
- `chore:` for maintenance

Format:
```
type(scope): short summary (50 chars or less)

Optional body explaining what and why (72 chars per line)
```

## Expected Output

A properly formatted commit message following conventional commits spec.

## Tips

- Paste the actual `git diff` for accuracy
- Mention the ticket/issue number if applicable
- Keep the summary under 50 characters
