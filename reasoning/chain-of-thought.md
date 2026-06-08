# Chain of Thought

**Category:** reasoning
**Model:** Any LLM
**Use case:** Solve complex problems step-by-step with transparent reasoning

## Prompt

Solve the following problem using chain-of-thought reasoning. Think step by step before giving the final answer.

Problem:
[Describe your problem in detail]

For each step:
1. State what you're trying to figure out
2. List the information you have
3. Apply logical rules or calculations
4. State your intermediate conclusion
5. Verify it against the original problem

Only after completing all steps, give the final answer.

## Expected Output

A step-by-step reasoning trace with intermediate conclusions and a verified final answer.

## Tips

- For math problems, show all calculations explicitly
- For logic puzzles, use diagrams or tables if helpful
- Ask for multiple approaches if the problem is open-ended
- Request verification: "Double-check your answer by working backwards"
