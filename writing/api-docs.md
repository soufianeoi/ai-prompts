# Write API Documentation

**Category:** writing
**Model:** Claude / GPT-4
**Use case:** Generate clear, developer-friendly API documentation

## Prompt

Write API documentation for the following endpoint:

```
Method: [GET / POST / PUT / DELETE]
Path: /api/[resource]
```

Include:
1. Description of what the endpoint does
2. Request headers (auth, content-type, etc.)
3. Request body schema (JSON with types)
4. Query parameters (if any)
5. Successful response example (200)
6. Error response examples (400, 401, 404, 500)
7. Rate limit info
8. cURL example

## Expected Output

Ready-to-publish documentation in markdown format with all sections filled out.

## Tips

- Provide the actual request/response JSON to make it concrete
- Mention any pagination strategy
- Include edge cases in error examples
- Ask for OpenAPI/Swagger format if needed
