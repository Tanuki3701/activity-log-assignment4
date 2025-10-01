# activity-log-assignment4
Repository for Assignment 4 - Deployment Pipeline with GitHub Actions
(作業 4 - 使用 GitHub Actions 的部署流水線)

```mermaid
graph TD
    A[Development (dev)] --> B[Staging (staging)]
    B --> C[Production (prod)]
    A -->|Build| D[Build Artifact]
    D --> B
    C -->|Manual Approval| E[Live Deployment]
