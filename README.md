# aws-dev-assoc

## AWS Regions 

- AWS has Regions all around the world.
- Names can be us-east-1, eu-west-3, etc.
- A region is a cluster of data centers.
- Most AWS services are region-scoped.

### How to choose an AWS Region?

- **Compliance with data governance and legal requirements**: Data never leaves a region without your explicit permission.
- **Proximity to customers**: Reduced latency.
- **Available services within a Region**: New services and new features aren’t available in every Region.
- **Pricing**: Pricing varies region to region and is transparent on the service pricing page.

## AWS Availability Zones

- Each region has many availability zones (usually 3, minimum is 3, maximum is 6). Example:
  - ap-southeast-2a
  - ap-southeast-2b
  - ap-southeast-2c
- Each availability zone (AZ) is one or more discrete data centers with redundant power, networking, and connectivity.
- They’re separate from each other, so that they’re isolated from disasters.
- They’re connected with high bandwidth, ultra-low latency networking.

## AWS Points of Presence (Edge Locations)

- Amazon has 400+ Points of Presence (400+ Edge Locations & 10+ Regional Caches) in 90+ cities across 40+ countries.
- Content is delivered to end users with lower latency.

  

| AWS Service | Use Case | Availability | Details |
| -------- | ------- | ------- | ------- | 
|Amazon EC2 | ... | ... | [EC2](https://github.com/Salman9193/aws-dev-assoc/blob/main/ec2/README.md)|
|Amazon ECR | ... | ... | link|
|Amazon ECS | ... | ... | link|
|AWS Elastic Beanstalk | ... | ... | link|
|AWS Lambda | ... | ... | link|
|Elastic Load Balancing | ... | ... | link|
|Amazon CloudFront | ... | ... | link|
|Amazon Kinesis | ... | ... | link|
|Amazon Route 53 | ... | ... | link|
|Amazon S3 | ... | ... | link|
|Amazon RDS | ... | ... | link|
|Amazon Aurora | ... | ... | link|
|Amazon DynamoDB | ... | ... | link|
|Amazon ElastiCache | ... | ... | link|
|Amazon SQS | ... | ... | link|
|Amazon SNS | ... | ... | link|
|AWS Step Functions | ... | ... | link|
|Auto Scaling | ... | ... | link|
|Amazon API Gateway | ... | ... | link|
|Amazon SES | ... | ... | link|
|Amazon Cognito | ... | ... | link|
|IAM | ... | ... | [IAM](https://github.com/Salman9193/aws-dev-assoc/blob/main/iam/README.md)|
|Amazon CloudWatch | ... | ... | link|
|Amazon EC2 Systems Manager | ... | ... | link|
|AWS CloudFormation | ... | ... | link|
|AWS CloudTrail | ... | ... | link|
|AWS CodeCommit | ... | ... | link|
|AWS CodeBuild | ... | ... | link|
|AWS CodeDeploy | ... | ... | link|
|AWS CodePipeline | ... | ... | link|
|AWS X-Ray | ... | ... | link|
|AWS KMS | ... | ... | link|

