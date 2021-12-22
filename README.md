# AWS-Work
All architectural design in AWS environment. Detailed step by step processes are mentioned in repo.
1) Build Highly available, Scalable, Self healing architecture to deploy WordPress application
![Scalable_Resilient_architecture_deployed WordPress application](https://user-images.githubusercontent.com/31379945/147038489-eccf6759-6b1e-4ab0-b698-54960486aa51.jpg)

2) Build an architecture to simulate on premise environment in AWS , hosted Maria DB in EC2 instance(simulated on premise) . Used Database Migration Service(DMS) to migrate Full copy of database for WordPress application to AWS Cloud MariaDB RDS DB instance using replica instance

![image](https://user-images.githubusercontent.com/31379945/147038929-acf7fa85-21b2-4fbe-b966-e9341bf6775a.png)

3) Build an architecture to deploy web applicaiton in EC2 instance , hosted in public subnet within VPC and used Route53 failover policy to failover to application , hosted in S3 (used S3 static webhosting feature).

![image](https://user-images.githubusercontent.com/31379945/147039419-83b9f24f-1de8-4692-ac8f-5fc6c4e21d97.png)

4) Build an architecture to implement HybridDNS using Route53 resolver endpoints- onpremise environment simulated in AWS

![image](https://user-images.githubusercontent.com/31379945/147039596-bfa7c643-166a-4ce8-88bd-7005b75aae8c.png)

5) Designed HA, secured architecture to deploy web applications built in MERN stack in AWS Cloud using EC2 (3 instances - 2 for frontend , 1 for backend), load balancer, Route 53 and Document DB services

![image](https://user-images.githubusercontent.com/31379945/120932846-2beb1780-c715-11eb-8747-ec05d086a981.png)

6)Optimized 3 Tier WEB application(MERN stack) (same application as mentioned in Point #5)  hosted in HA , Secured AWS environment using Container, ECR services

![image](https://user-images.githubusercontent.com/31379945/120932682-67d1ad00-c714-11eb-89e7-071f9f2a66ce.png)

7) Build an environment to host an application in S3 using static web hosting feature , distributed across  Cloudfront Edge location using Cloud front distribution, accessing bucket securely using OAI 

![image](https://user-images.githubusercontent.com/31379945/147041805-c57ec137-6ef8-4da0-acba-9d5472bbbd16.png)

8) Designed architecture to use Lambda in VPC , accessing EFS to load image from external API . Used by web application hosted in EC2 to display those images. Lambda is invoked by Event Bridge in every 5 mins interval

![image](https://user-images.githubusercontent.com/31379945/147042311-a4682c1a-433f-4a51-bcae-57954db3f2dc.png)

9) Designed framework to enable Federated user accessing private S3 bucket using Google IDP and Cognito Identity pool

![image](https://user-images.githubusercontent.com/31379945/147042478-6e2dca66-baaf-4c06-9d95-c17cd19accb4.png)


10)Upload an image to S3 and get notification to your mobile and email ID using Lambda, SNS topic.

![image](https://user-images.githubusercontent.com/31379945/120934174-e3365d00-c71a-11eb-8c2f-7ffb39ff557e.png)
