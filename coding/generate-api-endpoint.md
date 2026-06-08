# Generate a REST API Endpoint

**Category:** coding
**Model:** Any LLM
**Use case:** Generate a complete, production-ready API endpoint with validation, error handling, and documentation

## Prompt

`
Generate a REST API endpoint for [describe resource] with the following specifications:

Method: [GET/POST/PUT/DELETE]
Route: /api/[resource]
Authentication: [JWT / API key / none]
Database: [PostgreSQL / MongoDB / etc.]
Framework: [Express / FastAPI / etc.]

Requirements:
1. Input validation with proper error messages
2. Rate limiting
3. Pagination (for list endpoints)
4. Proper HTTP status codes
5. Error handling middleware
6. Unit tests
7. OpenAPI/Swagger documentation

Include:
- Request/response schemas
- Error response format
- Example curl commands
- Edge cases handled
`

## Expected Output

A complete, copy-pasteable endpoint with validation, error handling, tests, and docs. Structured for immediate use in a project.

## Tips

- Specify your exact framework and version for best results
- Include your database schema if applicable
- Ask for specific testing framework (Jest, pytest, etc.)