# AWS Cloud Security Hardening Project

## Project Overview

This project focused on securing and hardening a cloud-hosted web application environment deployed in AWS. The goal was to improve the security posture of the infrastructure by implementing defense-in-depth strategies across networking, storage, identity management, and application access controls.

The project involved securing an OWASP Juice Shop deployment using AWS-native security controls and validating the effectiveness of those controls through testing and verification procedures.

---

## Technologies Used

### Cloud & Infrastructure
- AWS EC2
- Amazon S3
- Application Load Balancer (ALB)
- VPC
- Security Groups
- Network ACLs (NACLs)

### Security & IAM
- IAM Policies
- RBAC / Least Privilege
- SSE-KMS Encryption
- Defense-in-Depth Architecture

### Tools & Platforms
- AWS Management Console
- Linux
- OWASP Juice Shop

---

## Security Improvements Implemented

### Network Security Hardening
- Restricted inbound traffic using Security Groups
- Implemented subnet-level filtering using NACLs
- Reduced unnecessary exposed ports
- Improved segmentation between application components

### Identity & Access Management
- Applied least privilege IAM permissions
- Restricted unauthorized S3 access
- Validated permission boundaries through testing

### Storage Security
- Enforced SSE-KMS encryption for S3 bucket objects
- Implemented bucket policy protections
- Prevented uploads without encryption enabled

### Application Security
- Secured OWASP Juice Shop deployment
- Restricted direct instance exposure
- Routed traffic through an Application Load Balancer

---

## Validation & Testing

Security controls were validated through multiple testing procedures, including:

- Access restriction validation
- IAM permission testing
- Encryption enforcement testing
- Connectivity and routing verification
- Application availability validation after hardening

---

## Repository Structure

```text
aws-cloud-security-hardening/
│
├── README.md
├── ENPM665FINALS.pdf
├── screenshots/
│
├── policies/
│   ├── bucket-policy.json
│   ├── iam-policy.json
│   └── security-group.json
│
└── architecture/
```

---

## Key Skills Demonstrated

- AWS Cloud Security
- IAM & Least Privilege
- Security Group Hardening
- Network Segmentation
- S3 Encryption (SSE-KMS)
- Infrastructure Security
- Application Security
- Cloud Architecture
- Risk Mitigation
- Security Validation & Testing

---

## Future Improvements

- Infrastructure as Code deployment using Terraform
- Automated compliance validation
- CloudWatch monitoring integration
- AWS Config security rule enforcement
- Containerized deployment using Docker
- CI/CD security scanning integration

---

## Documentation

The full technical implementation details, validation steps, and security configurations are included in:

```text
ENPM665FINALS.pdf
```

---

## Author

Ibaad Shaikh

M.Eng Cloud Engineering @ UMD  
Cybersecurity & Cloud Engineer  
Active DoD Secret Clearance
