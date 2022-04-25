# Infrastructure

## AWS Services

- S3:
  Amazon's s3 buckets are used to host the static front-end content of the application.
- Elastic Beanstalk:
  Elastic Beanstalk is used to host the Back-end api, using a Node.js Environment.
- RDS:
  The RDS service is used to host the database needed for the api, Using PostgreSQL.

## CircleCI/The Pipeline

CircleCi is used for creating a pipeline to deploy the application, using the source code hosted on GitHub, and AWS Cli.
