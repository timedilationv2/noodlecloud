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

---

**Home | Previous | Next**

**Arsalan Khan | Artifix Labs | Seattle, Washington | 2025**
