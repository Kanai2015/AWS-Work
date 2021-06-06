# AWS-Work
All architectural design in AWS environment. Detailed step by step processes are mentioned in repo.

1) Designed highly available, secured architecture to deploy web applications built in MERN stack in AWS Cloud using EC2 (3 instances - 2 for frontend , 1 for backend), load balancer, Route 53 and Document DB services

![image](https://user-images.githubusercontent.com/31379945/120932846-2beb1780-c715-11eb-8747-ec05d086a981.png)

2)Optimized 3 Tier WEB application(MERN stack) (same application as mentioned in Point #1)  hosted in High Available , Secured AWS environment using Container, ECR services

![image](https://user-images.githubusercontent.com/31379945/120932682-67d1ad00-c714-11eb-89e7-071f9f2a66ce.png)


3)Connect RDS from private EC2 at private subnet. Private EC2 is to be connected from EC2   located at public subnet in user defined Virtual Private Cloud.

![image](https://user-images.githubusercontent.com/31379945/120934078-86d33d80-c71a-11eb-8552-dbb270229c13.png)

4)Return date and time from web application built on T2 Micro EC2 instance in Auto Scaling Group. It is to accessed by Application Load Balancer, which is in-turn to be accessed by Route 53.

![image](https://user-images.githubusercontent.com/31379945/120934115-a702fc80-c71a-11eb-9113-0375f55011d1.png)

5)Upload an image to S3 and get notification to your mobile and email ID using Lambda, SNS topic.

![image](https://user-images.githubusercontent.com/31379945/120934174-e3365d00-c71a-11eb-8c2f-7ffb39ff557e.png)
