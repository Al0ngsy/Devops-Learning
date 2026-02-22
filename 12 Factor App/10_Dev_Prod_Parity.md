## 10. Dev/Prod Parity

Development, staging, and production environments should be as similar as possible to reduce bugs and issues from environment differences.

This includes:
- Same backing services (databases, message queues) in the same version/schema
- Same configuration management (environment variables with same keys but different values per environment)
- Same deployment processes (CI/CD pipelines) across all environments
- Feature developers participate in the deployment process to ensure issues can be easily reproduced and fixed
