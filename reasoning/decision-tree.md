# Decision Tree

**Category:** reasoning
**Model:** Any LLM
**Use case:** Map out complex decisions with branching outcomes and probabilities

## Prompt

Build a decision tree for the following choice:

Decision to make: [describe the decision]
Options: [list the available choices]
Key uncertainties: [what you don't know]
Time horizon: [short-term / long-term]

For each option, map out:
1. Best case outcome (with probability estimate)
2. Most likely outcome (with probability estimate)
3. Worst case outcome (with probability estimate)
4. Regret factor — if this fails, how bad is it?
5. Reversibility — can you undo this choice?

Then calculate:
- Expected value for each option
- Risk-adjusted recommendation
- A "no-regret" move (something beneficial regardless of outcome)

## Expected Output

A structured decision tree with probabilities, expected values, risk assessment, and a clear recommendation.

## Tips

- Be honest about probabilities (don't inflate confidence)
- Include "do nothing" as an option
- Ask for a pre-mortem: "It's 1 year later and this failed — why?"
- Request a checklist of signals that indicate you chose wrong
