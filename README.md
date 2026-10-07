# AWS Data Protection, Encryption & Privacy Compliance

Graduation project for the Digital Egypt Pioneers Initiative (DEPI), Cloud Security track.

We build a complete data protection setup on AWS: classify data, encrypt it at rest and in transit, manage keys and secrets, find sensitive data automatically, and map everything to GDPR, HIPAA, and PCI-DSS. All testing uses synthetic data only.

## Team

- Marwa Abdullah Ouf Elzoghby
- Nadine Amr Sayed Fahmy
- Omar Mohsen Emam Youssef
- Zyad Ahmed Mahmoud Ibrahim
- Dina Bahy Mostafa El-shiekh
- Haneen Mosad Mohammed Elgebaly

Instructor: Samah Esia

## What We Build

| Week | Focus | Main deliverables |
|---|---|---|
| 1 | Data lifecycle, classification, S3 security | Classification scheme, S3 secure baseline, bucket policies, lifecycle policy |
| 2 | Encryption at rest and key management | KMS key hierarchy, key policies, encrypted data stores, KMS lab evidence |
| 3 | Encryption in transit, secrets, API protection | TLS/ACM setup, secrets rotation design, API security controls |
| 4 | Data in use, DLP, privacy, compliance | Macie findings report, DLP plan, compliance control matrix, risk register |

## AWS Services Used

S3, KMS, RDS, DynamoDB, EBS, Glacier, ACM, Secrets Manager, Parameter Store, API Gateway, Macie, GuardDuty, CloudTrail, Security Hub, IAM, Access Analyzer.

CloudHSM is covered as a concept only.

## Repository Structure

```
.
├── docs/         # Proposal and final report
├── terraform/    # Infrastructure as code
├── evidence/     # Screenshots and lab results
└── README.md
```

## Getting Started

```bash
git clone https://github.com/marwa-elzoghby/AWS-Security-project-DEPI.git
cd AWS-Security-project-DEPI
git pull
```

Before you push, always run `git pull` first so you don't overwrite a teammate's work.

## Important Notes

- Use synthetic (fake) data only. Never upload real personal or payment data.
- Never commit AWS access keys, secrets, or `.tfstate` files.
- Delete AWS resources after each lab to avoid unexpected costs.
