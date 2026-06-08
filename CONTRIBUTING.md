# Contributing to AI Prompts

Prompts are welcome! Please follow these guidelines to keep the collection consistent and high-quality.

## Prompt Requirements

- **Tested:** Run the prompt at least once and verify the output
- **Original:** Don't copy prompts from other collections
- **Useful:** Solves a real, reusable problem
- **Complete:** Follows the standard format (title, category, use case, prompt, expected output, tips)
- **Generic:** Uses `[bracketed placeholders]` so others can adapt

## Adding a Prompt

1. Choose the right category folder (`coding/`, `writing/`, `analysis/`, `creative/`, `reasoning/`)
2. Create a new `.md` file with a descriptive kebab-case name
3. Follow this template:

```markdown
# Title

**Category:** category
**Model:** Recommended model(s)
**Use case:** One-line description

## Prompt

Template text with [placeholders].

## Expected Output

Brief description.

## Tips

- Tip 1
- Tip 2
```

4. Add your prompt to the index table in `README.md`
5. Create a Pull Request

## Style Guide

- Use `[square brackets]` for placeholders
- Keep prompts model-agnostic where possible (note model-specific tips separately)
- One idea per prompt
- Lead with the task, then add constraints
- Include at least 3 tips per prompt

## Code of Conduct

Be excellent to each other.
