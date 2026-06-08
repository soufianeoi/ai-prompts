# Decision Matrix

**Category:** analysis
**Model:** Any LLM
**Use case:** Compare options systematically using weighted criteria

## Prompt

Help me make a decision. Here are my options and criteria:

**Options:**
- Option A: [description]
- Option B: [description]
- Option C: [description]

**Criteria** (rate importance 1-5):
- [Criterion 1]: importance [1-5]
- [Criterion 2]: importance [1-5]
- [Criterion 3]: importance [1-5]

For each option, rate each criterion 1-5 and calculate weighted scores.

Also provide:
- Pros and cons of each option
- Risk assessment for top choices
- Recommendation with reasoning
- Questions I should ask myself before deciding

## Expected Output

A scored decision matrix table with weighted rankings, pros/cons, and a clear recommendation.

## Tips

- Be honest about your constraints (budget, time, skills)
- Include intangibles that are hard to quantify
- Ask for a "second opinion" counter-argument to the recommendation
