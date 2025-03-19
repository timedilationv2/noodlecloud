# NoodleCloud Usage Guide

This guide explains how to use NoodleCloud to **execute cloud-based tests**.

## Running a Cloud Test

```bash
curl -X POST "https://api.noodlecloud.com/tests/create" -H "Content-Type: application/json" -d '{
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

| Section | Description |
|---------|-------------|
| [Setup Guide](./setup.md) | Steps to set up the project |
| [API Reference](./api_reference.md) | API details & endpoints |

---

### Navigation  
[← Setup Guide](./setup.md) | [API Reference →](./api_reference.md)

---

**Arsalan Khan | Artifix Labs | Seattle, Washington | 2025**
