# Design a REST API

**Category:** coding
**Model:** Any LLM
**Use case:** Design a complete REST API with endpoints, schemas, and best practices

## Prompt

Design a REST API for [describe system, e.g. "a task management app"].

Requirements:
- Users can create, read, update, delete tasks
- Tasks have: title, description, status, priority, due date, assignee
- Users can filter tasks by status, priority, and date range
- Tasks can have tags
- Authentication via JWT
- Rate limiting: 100 req/min per user

Please provide:
1. Complete endpoint list with HTTP methods and paths
2. Request/response schemas (JSON)
3. Authentication flow
4. Error response format
5. Pagination strategy
6. Status codes for each endpoint

## Expected Output

A complete API specification with endpoints, schemas, auth flow, and error handling strategy.

## Tips

- Specify your tech stack (Express, FastAPI, etc.)
- Ask for OpenAPI/Swagger YAML output
- Include real-world edge cases (concurrent edits, deleted resources)
