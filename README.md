My portfolio

# Serverless Resume Website on AWS

## Overview

This project demonstrates a **fully serverless resume website hosted on AWS**, designed to showcase practical cloud skills and architectural understanding. Rather than just listing skills on a resume, this project allows you to **showcase AWS expertise in action**, including serverless architecture, infrastructure as code, security, and performance optimization.

The website is **fast, secure, cost-effective, and scalable**, making it both a professional online portfolio and a practical demonstration of cloud capabilities.

---

## Architecture

The project leverages key AWS services:

* **Amazon S3**: Hosts the static website (HTML, CSS, JavaScript) with durability and high availability.
* **Amazon CloudFront**: Delivers content globally via edge locations for low-latency access.
* **Route 53**: Provides a professional custom domain and DNS management.
* **AWS Certificate Manager (ACM)**: Secures the site with HTTPS.
* **AWS Lambda & API Gateway**: Powers dynamic features like visitor counters or contact forms.
* **DynamoDB**: Tracks visitor statistics in a serverless, scalable NoSQL database.
* **CI/CD Pipeline**: Uses GitHub Actions or AWS CodePipeline for automated deployment on updates.

Optional enhancements include visitor tracking, interactive forms, and dynamic content—all implemented **serverlessly**.

---

## Implementation Steps

1. **Design Resume Website**: Create HTML/CSS layout with responsive design.
2. **Version Control**: Upload files to GitHub for backup and CI/CD integration.
3. **Domain & Hosting**: Register a domain and configure S3 for secure static hosting.
4. **CloudFront Distribution**: Serve content globally with HTTPS and cache optimization.
5. **DNS Configuration**: Connect domain to CloudFront using Route 53 or external DNS.
6. **Infrastructure as Code**: Define architecture using CloudFormation, CDK, or Terraform.
7. **Serverless Features**: Add Lambda + API Gateway for dynamic interactions and DynamoDB for visitor stats.
8. **CI/CD Deployment**: Automate website updates and cache invalidation on changes.

---

## Key Benefits

* **Practical Demonstration of AWS Skills**: Infrastructure, serverless services, security, and CI/CD.
* **Interview Conversation Starter**: Architecture and design decisions become talking points.
* **Cost-Effective**: Minimal AWS charges; can run almost entirely on Free Tier.
* **Secure & Scalable**: Best practices implemented for HTTPS, least privilege IAM, and logging.

---

## Security & Best Practices

* Bucket policies prevent unauthorized access.
* Encryption for sensitive data at rest (S3, DynamoDB).
* IAM roles follow least privilege principle.
* CloudFront & S3 access logging enabled.
* HTTPS enforced using ACM certificates.

---

## Conclusion

This **Serverless Resume Website** transforms a static resume into a **living portfolio** that demonstrates real-world AWS cloud skills. It’s an evolving project where features can be expanded as your skills grow, making it a strong differentiator for potential employers.

---


