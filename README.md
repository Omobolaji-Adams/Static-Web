# Project Overview
The cloud is perfect for hosting static websites that only include HTML, CSS, and JavaScript files that require no server-side processing.
---
Hosted a static website on S3 and
Accessed the cached website pages using CloudFront content delivery network (CDN) service. Utilizing CloudFront's low latency and high transfer speeds during website rendering.
Static website hosting essentially requires a public bucket, CloudFront can work with public and private buckets.

In this project, i deployed a static website to AWS by performing the following steps:

Created a public S3 bucket and uploaded the website files to my bucket.
Configured the bucket for website hosting and secured it using IAM policies.
Sped up content delivery using AWS’s content distribution network service, CloudFront.
Accessed my website in a browser using the unique CloudFront endpoint.

### AWS concepts Covered:
S3 bucket creation
S3 bucket configuration
Website distribution via CloudFront
Access website via web browser

### Dependencies
Cloud Services
Amazon Web Services S3 - Resource hosting and deployments
AWS CloudFront - CDN for SPA
AWS EKS - Backend API
AWS DynamoDB - Persistent Datastore
AWS Cognito - User Authentication
Performance Tracking and DevOps Tools:
AWS CloudWatch - Performance and Health checks
Sentry - Bug Reporting

### Frameworks:
Ionic (Javascript) (Frontend)
Node.js (Javascript) (Backend)
