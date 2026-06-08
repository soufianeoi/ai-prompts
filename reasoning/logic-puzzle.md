# Logic Puzzle Solver

**Category:** reasoning
**Model:** Any LLM
**Use case:** Solve grid-based logic puzzles, riddles, and deduction problems

## Prompt

Solve this logic puzzle:

[Describe the puzzle, including all rules, constraints, and known facts]

Use a grid or elimination table if helpful. For each deduction:
1. State what rule you're applying
2. Show what possibilities are eliminated
3. State the new fact you've established

Continue until all cells are determined.

## Expected Output

A step-by-step deduction with elimination tracking and the final solution.

## Tips

- Format the puzzle clearly with numbered clues
- For grid puzzles, describe the dimensions (e.g., "3 people x 3 attributes")
- Ask for the reasoning in a format you can verify
- Request a truth table for binary logic puzzles
