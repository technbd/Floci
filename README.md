## Floci:

Floci is a fast, free, open-source local AWS emulator. It lets you run AWS CLI commands against it locally — no real AWS account needed. Floci It's similar to **LocalStack**. 

It is mainly positioned as a drop-in replacement for **LocalStack** Community Edition, especially after **LocalStack** introduced restrictions and auth tokens.


### Key features:

_Supports many common services like (35 AWS services supported):_
- S3
- SQS / SNS
- DynamoDB (+ Streams)
- Lambda (Docker-based execution)
- API Gateway (v2)
- IAM / STS
- KMS
- CloudFormation
- Secrets Manager
- Step Functions
- RDS (PostgreSQL / MySQL)
- ElastiCache (Redis)
- CloudWatch Logs
- Cognito
- ECR
- EC2 
- EKS 
- OpenSearch



### Why Floci?


| Feature / Capability | Floci | LocalStack Community |
|---------------------|-------|---------------------|
| Auth token required | No | Yes (since March 2026) |
| Security updates | Yes | Frozen |
| Startup time | ~24 ms | ~3.3 s |
| Idle memory | ~13 MiB | ~143 MiB |
| Docker image size | ~90 MB | ~1.0 GB |
| License | MIT | Restricted |
| API Gateway v2 / HTTP API | ✅ | ❌ |
| Cognito | ✅ | ❌ |
| ElastiCache (Redis + IAM auth) | ✅ | ❌ |
| RDS (PostgreSQL + MySQL + IAM auth) | ✅ | ❌ |
| MSK (Kafka + Redpanda) | ✅ | ❌ |
| Athena (query state machine, mock mode) | ✅ | ❌ |
| Glue Data Catalog | ✅ | ❌ |
| Data Firehose (NDJSON delivery) | ✅ | ❌ |
| S3 Object Lock (COMPLIANCE / GOVERNANCE) | ✅ | ⚠️ Partial |
| DynamoDB Streams | ✅ | ⚠️ Partial |
| IAM (users, roles, policies, groups) | ✅ | ⚠️ Partial |
| STS (all 7 operations) | ✅ | ⚠️ Partial |
| Kinesis (streams, shards, fan-out) | ✅ | ⚠️ Partial |
| KMS (sign, verify, re-encrypt) | ✅ | ⚠️ Partial |
| ECS (clusters, services, tasks) | ✅ | ❌ |
| EKS (clusters, mock + real k3s) | ✅ | ❌ |
| EC2 (VPCs, instances, security groups) | ✅ | ⚠️ Partial |
| Native binary | ✅ (~40 MB) | ❌ |






### When to use Floci:

- Local AWS development
- CI/CD testing without AWS cost
- Terraform testing
- Integration tests for cloud apps
- Replacing LocalStack community usage




---
---


### Ref:
- [Floci Installation](https://floci.io/floci/getting-started/installation/)
- [Floci Environment Variables Reference](https://floci.io/floci/configuration/environment-variables/)
- [Floci | github.com](https://github.com/floci-io/floci)


