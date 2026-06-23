# Poc_24

# ECS Fargate CI/CD POC

## Architecture
GitHub → CodePipeline → CodeBuild → ECR → ECS Fargate → ALB

## Steps
1. Dockerize app
2. Push to ECR
3. Deploy using ECS Fargate
4. Automate with CodePipeline

## Output
App exposed via ALB
