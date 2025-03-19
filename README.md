# CloudNoodle API

**CloudNoodle** is a scalable, multi-cloud **testing API** designed for seamless **infrastructure validation, load testing, and continuous deployment checks**.

## Key Features

| Feature                  | Description |
|--------------------------|-------------|
| **Multi-Cloud Support**  | AWS, Azure, GCP compatibility |
| **Automated Test Execution** | Runs in CI/CD pipelines |
| **Performance Benchmarking** | Simulate real-world cloud loads |
| **Infrastructure Validation** | Checks configurations & deployments |
| **Security Compliance** | Validates policies & cloud best practices |

## Repository Structure

| Folder  | Description |
|---------|------------|
| `docs/` | Documentation files |
| `src/`  | API source code |
| `tests/` | Test scripts & validation checks |

## Installation

```bash
git clone https://github.com/timedilationv2/cloudnoodle.git
cd cloudnoodle
pip install -r requirements.txt
```

## Documentation
- [Architecture](docs/architecture.md)
- [Setup Guide](docs/setup.md)
- [Usage Guide](docs/usage.md)
- [API Reference](docs/api_reference.md)

---

## Get Started

### Run the API Locally
```bash
uvicorn cloudnoodle:app --reload
```

---

## Contact  
For inquiries, visit [timedilationv2 on GitHub](https://github.com/timedilationv2)
