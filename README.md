# Shared AWS API Gateway

Working on production projects would often require the usage of a shared API gateway between multiple Lambda functions. This repository showcases how to deploy multiple Lambda functions that are attached on a single API gateway.

## Add execution permission to CI deploy + decomission scripts.

```sh
chmod +x .\ci-deploy.sh
chmod +x .\ci-decomission.sh
```

### Configure your AWS Deployment Account

Provide an AWS account that have sufficient access so that serverless can deploy the stack.

```sh
serverless config credentials --provider aws --key YOUR_AWS_ACCESS_KEY --secret YOUR_AWS_SECRET_KEY
```

# Deploying the API Gateway + Lambda Stack

To deploy the

```sh
.\ci-deploy
```

# Decomission all resources

```sh
.\ci-decomission
```
