# Cloud Resume Challenge

## Project Purpose

Build and deploy a cloud-native resume using the Cloud Resume Challenge spec:
https://cloudresumechallenge.dev/docs/the-challenge/

## Target Stack

- **Frontend:** Static HTML/CSS resume hosted on S3, served via CloudFront
- **DNS:** Route 53 custom domain
- **Backend:** Visitor counter — API Gateway + Lambda (Python) + DynamoDB
- **IaC:** Terraform or AWS SAM (TBD)
- **CI/CD:** GitHub Actions

## Repository Structure

```
cloud-resume-challenge/
├── CLAUDE.md
├── session_log.md
├── frontend/          # HTML, CSS, JS
├── backend/           # Lambda function(s)
├── infrastructure/    # IaC (Terraform or SAM)
└── .github/workflows/ # CI/CD pipelines
```

## Reference

- `The Cloud Resume Challenge Guidebook - AWS Edition.txt` — full project walkthrough

## GitHub Account

`darrel-wallace` (professional project)
