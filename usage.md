# CloudNoodle Usage Guide

This guide explains how to use CloudNoodle to **run cloud-based tests**.

## Running a Cloud Test

```bash
curl -X POST "https://api.cloudnoodle.com/tests/create" -H "Content-Type: application/json" -d '{
    "test_name": "Cloud Deployment Validation",
    "cloud_provider": "AWS",
    "resources": ["EC2", "RDS", "Lambda"]
}'
```

## Best Practices

| Tip | Description |
|-----|-------------|
| Use versioning | Keep track of API updates |
| Monitor logs | Enable logging for debugging |
| Secure API Keys | Use environment variables to store keys |

## Related Docs

- [Setup Guide](setup.md)
- [API Reference](api_reference.md)
