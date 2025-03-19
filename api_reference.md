# API Reference

## Authentication

```bash
curl -X POST "https://api.noodlecloud.com/auth/login" -d '{
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

| Section | Description |
|---------|-------------|
| [Usage Guide](usage.md) | Running tests and best practices |
| [Setup Guide](setup.md) | Steps to set up the project |

---

### Navigation  
[← Usage Guide](usage.md) | [Contribution Guide →](contributing.md)

---

**Arsalan Khan | Artifix Labs | Seattle, Washington | 2025**
