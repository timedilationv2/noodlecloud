# API Reference

## Authentication

```bash
curl -X POST "https://api.cloudnoodle.com/auth/login" -d '{
    "username": "user",
    "password": "pass"
}'
```

## Endpoints

| Method | Endpoint | Description |
|--------|---------|------------|
| **GET** | `/tests` | Retrieve all tests |
| **POST** | `/tests/create` | Create a new cloud test |
| **GET** | `/results/:id` | Get test execution results |
| **DELETE** | `/tests/:id` | Remove a test |

## Related Docs

- [Usage Guide](usage.md)
- [Setup Guide](setup.md)
