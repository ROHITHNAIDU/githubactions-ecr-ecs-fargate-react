Github Actions, ECR, ECS-fargate, React app
1. using Github Actions the docker image will be built and pushed to ECR Repository.
2. The ECS task definition file is updated with latest image id and it is deployed to Amazon ECS cluster.
3. Access the app using the public ip of the task or load balancer uRL.
