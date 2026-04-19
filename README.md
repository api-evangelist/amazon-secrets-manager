# Amazon Secrets Manager
Amazon Secrets Manager helps you manage, retrieve, and rotate database credentials, API keys, and other secrets throughout their lifecycle. It provides centralized secrets management with built-in integration for Amazon RDS, Amazon Redshift, and Amazon DocumentDB, enabling automatic rotation of secrets without requiring application changes.

**URL:** [Visit APIs.json URL](https://aws.amazon.com/secrets-manager/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Configuration, Credentials, Rotation, Secrets, Security

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-19

## APIs

### Amazon Secrets Manager API
The Amazon Secrets Manager API for creating, managing, retrieving, and rotating secrets including database credentials, API keys, and other sensitive configuration.

**Human URL:** [https://docs.aws.amazon.com/secretsmanager/latest/apireference/](https://docs.aws.amazon.com/secretsmanager/latest/apireference/)

#### Tags:

 - Security, Secrets, Credentials, Rotation

#### Properties

- [Documentation](https://docs.aws.amazon.com/secretsmanager/latest/apireference/)
- [OpenAPI](openapi/amazon-secrets-manager-openapi.yml)
- [JSONSchema](json-schema/amazon-secrets-manager-secret-schema.json)
- [JSONSchema](json-schema/amazon-secrets-manager-secret-value-schema.json)
- [JSONSchema](json-schema/amazon-secrets-manager-rotation-rules-schema.json)

## Common Properties

- [Portal](https://aws.amazon.com/)
- [GettingStarted](https://aws.amazon.com/secrets-manager/getting-started/)
- [Documentation](https://docs.aws.amazon.com/secretsmanager/latest/userguide/)
- [APIReference](https://docs.aws.amazon.com/secretsmanager/latest/apireference/)
- [Console](https://console.aws.amazon.com/secretsmanager/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [Pricing](https://aws.amazon.com/secrets-manager/pricing/)
- [FAQ](https://aws.amazon.com/secrets-manager/faqs/)
- [Blog](https://aws.amazon.com/blogs/security/)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Support](https://aws.amazon.com/support/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Security](https://docs.aws.amazon.com/secretsmanager/latest/userguide/security.html)
- [Compliance](https://aws.amazon.com/compliance/)
- [GitHubOrganization](https://github.com/aws)
- [YouTube](https://www.youtube.com/user/AmazonWebServices)
- [StackOverflow](https://stackoverflow.com/questions/tagged/aws-secrets-manager)
- [KnowledgeCenter](https://repost.aws/knowledge-center)
- [CLI](https://docs.aws.amazon.com/cli/latest/reference/secretsmanager/)
- [SpectralRules](rules/amazon-secrets-manager-spectral-rules.yml)
- [Vocabulary](vocabulary/amazon-secrets-manager-vocabulary.yaml)
- [NaftikoCapability](capabilities/secrets-management.yaml)
- [JSON-LD](json-ld/amazon-secrets-manager-context.jsonld)
- [JSONSchema](json-schema/amazon-secrets-manager-get-random-password-response-schema.json)
- [JSONSchema](json-schema/amazon-secrets-manager-list-secrets-response-schema.json)
- [JSONSchema](json-schema/amazon-secrets-manager-tag-schema.json)
- [JSONStructure](json-structure/amazon-secrets-manager-get-random-password-response-structure.json)
- [JSONStructure](json-structure/amazon-secrets-manager-list-secrets-response-structure.json)
- [JSONStructure](json-structure/amazon-secrets-manager-rotation-rules-structure.json)
- [JSONStructure](json-structure/amazon-secrets-manager-secret-structure.json)
- [JSONStructure](json-structure/amazon-secrets-manager-secret-value-structure.json)
- [JSONStructure](json-structure/amazon-secrets-manager-tag-structure.json)
- [Example](examples/amazon-secrets-manager-get-random-password-response-example.json)
- [Example](examples/amazon-secrets-manager-list-secrets-response-example.json)
- [Example](examples/amazon-secrets-manager-rotation-rules-example.json)
- [Example](examples/amazon-secrets-manager-secret-example.json)
- [Example](examples/amazon-secrets-manager-secret-value-example.json)
- [Example](examples/amazon-secrets-manager-tag-example.json)
- [NaftikoCapability](capabilities/shared/amazon-secrets-manager.yaml)

## Features

| Name | Description |
|------|-------------|
| Automatic Secret Rotation | Automatically rotate secrets on a schedule using AWS Lambda rotation functions without changing application code. |
| Centralized Secret Storage | Store and manage all secrets in a single, centralized location with fine-grained access controls. |
| Native Database Integration | Built-in integration with Amazon RDS, Aurora, Redshift, and DocumentDB for automatic credential rotation. |
| Secret Versioning | Maintain multiple versions of a secret simultaneously to support zero-downtime rotation. |
| Audit and Compliance | Log all secret access and management actions via AWS CloudTrail for compliance and audit purposes. |
| Cross-Account Access | Share secrets across AWS accounts using resource-based policies. |
| Encryption at Rest | All secrets are encrypted at rest using AWS KMS keys you control. |
| Random Password Generation | Generate cryptographically secure random passwords with configurable complexity requirements. |

## Use Cases

| Name | Description |
|------|-------------|
| Database Credential Management | Automatically rotate and manage database credentials for RDS, Aurora, and other databases. |
| API Key Storage | Securely store and retrieve API keys, OAuth tokens, and other third-party service credentials. |
| Application Configuration | Centralize sensitive application configuration such as connection strings and encryption keys. |
| Cross-Service Credentials | Share service-to-service credentials securely across microservices without embedding in code. |
| Compliance Secret Rotation | Meet compliance requirements like PCI DSS and SOC 2 by enforcing regular credential rotation. |
| Secrets Lifecycle Governance | Enforce organizational policies on secret creation, rotation schedules, and access patterns. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon RDS | Native integration for automatic rotation of RDS database credentials. |
| Amazon Aurora | Built-in support for rotating Aurora database master user passwords. |
| Amazon Redshift | Automatic rotation of Redshift cluster credentials. |
| Amazon DocumentDB | Native rotation support for DocumentDB user credentials. |
| AWS Lambda | Lambda-powered custom rotation functions for any secret type. |
| AWS CloudTrail | Audit logging of all Secrets Manager API calls via CloudTrail. |
| AWS KMS | Encryption of secrets at rest using customer-managed KMS keys. |
| AWS IAM | Fine-grained access control for secrets using IAM policies and resource-based policies. |
| AWS CloudFormation | Provision and manage secrets as part of CloudFormation stacks. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [amazon-secrets-manager-openapi.yml](openapi/amazon-secrets-manager-openapi.yml)

### JSON Schema

- [amazon-secrets-manager-get-random-password-response-schema.json](json-schema/amazon-secrets-manager-get-random-password-response-schema.json)
- [amazon-secrets-manager-list-secrets-response-schema.json](json-schema/amazon-secrets-manager-list-secrets-response-schema.json)
- [amazon-secrets-manager-rotation-rules-schema.json](json-schema/amazon-secrets-manager-rotation-rules-schema.json)
- [amazon-secrets-manager-secret-schema.json](json-schema/amazon-secrets-manager-secret-schema.json)
- [amazon-secrets-manager-secret-value-schema.json](json-schema/amazon-secrets-manager-secret-value-schema.json)
- [amazon-secrets-manager-tag-schema.json](json-schema/amazon-secrets-manager-tag-schema.json)

### JSON Structure

- [amazon-secrets-manager-get-random-password-response-structure.json](json-structure/amazon-secrets-manager-get-random-password-response-structure.json)
- [amazon-secrets-manager-list-secrets-response-structure.json](json-structure/amazon-secrets-manager-list-secrets-response-structure.json)
- [amazon-secrets-manager-rotation-rules-structure.json](json-structure/amazon-secrets-manager-rotation-rules-structure.json)
- [amazon-secrets-manager-secret-structure.json](json-structure/amazon-secrets-manager-secret-structure.json)
- [amazon-secrets-manager-secret-value-structure.json](json-structure/amazon-secrets-manager-secret-value-structure.json)
- [amazon-secrets-manager-tag-structure.json](json-structure/amazon-secrets-manager-tag-structure.json)

### JSON-LD

- [amazon-secrets-manager-context.jsonld](json-ld/amazon-secrets-manager-context.jsonld)

### Examples

- [amazon-secrets-manager-get-random-password-response-example.json](examples/amazon-secrets-manager-get-random-password-response-example.json)
- [amazon-secrets-manager-list-secrets-response-example.json](examples/amazon-secrets-manager-list-secrets-response-example.json)
- [amazon-secrets-manager-rotation-rules-example.json](examples/amazon-secrets-manager-rotation-rules-example.json)
- [amazon-secrets-manager-secret-example.json](examples/amazon-secrets-manager-secret-example.json)
- [amazon-secrets-manager-secret-value-example.json](examples/amazon-secrets-manager-secret-value-example.json)
- [amazon-secrets-manager-tag-example.json](examples/amazon-secrets-manager-tag-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [amazon-secrets-manager.yaml](capabilities/shared/amazon-secrets-manager.yaml)

### Workflow Capabilities

- [secrets-management.yaml](capabilities/secrets-management.yaml)

## Vocabulary

- [amazon-secrets-manager-vocabulary.yaml](vocabulary/amazon-secrets-manager-vocabulary.yaml)

## Rules

- [amazon-secrets-manager-spectral-rules.yml](rules/amazon-secrets-manager-spectral-rules.yml)

