# CloudNoodle Architecture

CloudNoodle follows a **microservices-based architecture** designed for scalability and integration with cloud services.

## System Components

| Component        | Description |
|-----------------|-------------|
| API Gateway     | Routes API requests securely |
| Test Execution Engine | Manages & runs cloud-based tests |
| Cloud SDK Adapters | Interfaces with AWS, Azure, and GCP |
| Result Processor | Aggregates test results & performance metrics |

## Architecture Diagram

```plaintext
[Client] ---> [API Gateway] ---> [Execution Engine] ---> [Cloud Provider SDKs]
                 |
                 ---> [Database] ---> [Result Processor]
```

## Related Docs
- [Setup Guide](setup.md)
- [Usage Guide](usage.md)
