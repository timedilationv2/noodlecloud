# NoodleCloud

**Cloud-native testing API** designed for **infrastructure validation, automated load testing, and security compliance**.

---

## Technology Stack

- **Backend:** Python (FastAPI)
- **Cloud SDKs:** AWS SDK (Boto3), Azure SDK, Google Cloud SDK
- **Database:** PostgreSQL (Cloud logs), Redis (Caching results)
- **CI/CD:** GitHub Actions + Terraform for cloud infrastructure
- **Security Checks:** AWS Security Hub, Azure Security Center, GCP Policy Scanner

---

## Key Features

| Feature                   | Description |
|---------------------------|-------------|
| Multi-Cloud Support       | Compatible with AWS, Azure, and GCP |
| Automated Test Execution  | Runs in CI/CD pipelines |
| Performance Benchmarking  | Simulates real-world cloud workloads |
| Infrastructure Validation | Ensures correct configurations and deployments |
| Security Compliance       | Detects policy violations and misconfigurations |

---

## Repository Structure

| Folder  | Description |
|---------|------------|
| [docs/](./docs/) | Documentation files |
| [src/](./src/)  | API source code |
| [tests/](./tests/) | Unit and integration tests |
| [scripts/](./scripts/) | Utility and automation scripts |

---

## Installation & Setup

```bash
git clone https://github.com/timedilationv2/noodlecloud.git
cd noodlecloud
pip install -r requirements.txt
```

---

**Home | Previous | Next**

**Arsalan Khan | Artifix Labs | Seattle, Washington | 2025**
