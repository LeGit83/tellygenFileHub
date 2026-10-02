
# Tellygent FileHub

A secure, serverless digital-asset management system built on AWS.

FileHub allows authenticated users to upload, store, manage and process files, with an event-driven backend handling what happens after upload.

## Why I'm building this

FileHub is my hands-on AWS laboratory for turning DVA-C02 concepts into practical skills in architecture, implementation, troubleshooting, security and cost-aware design.

The project is being built incrementally: each AWS service is introduced to solve a real requirement rather than simply to demonstrate the service.

## Current Architecture

```text
Browser
   │
   ▼
API Gateway HTTP API
   │
   ▼
Lambda
   │
   ▼
S3
