# AWS Interview Questions

1. What is VPC

2. What is the difference between subnet and security group

3. When do you choose dnyamodb over S3

4. What are the different indexes on dynamodb

5. What is the default Timeout of lambda

6. What is a dead letter queue in SQS

7. What is CAP theorem and In terms of the CAP theorem, explain DynamoDB

Ans: In terms of the CAP theorem, DynamoDB is an Available & Partition-tolerant (AP) database with eventual write consistency. On the read front, it supports both eventually consistent and strongly consistent reads. However, strongly consistent reads in DynamoDB are not highly available in the presence of network delays and partitions. Since such failures are common in multi-region/global apps running on public clouds such as AWS, DynamoDB tries to reduce such failures by limiting strongly consistent reads only to a single region. This in turn makes DynamoDB unfit for most multi-region apps and an unreliable solution for even single-region apps.

8. How do you setup website with S3

9. Difference between policy and role

10. Why do you need a role

11. How do you manage configurations

12. How do you deploy the code in AWS
