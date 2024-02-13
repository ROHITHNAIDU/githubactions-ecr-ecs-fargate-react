Github Actions, ECR, ECS-Fargate, React app

1. using Github Actions the docker image will be built and pushed to ECR Repository.
2. The ECS task definition file is updated with latest image id, using this task def file the container is automatically deployed/created to/in Amazon ECS/fargate cluster.
3. Access the app using the public ip of the task or load balancer URL.

source : https://awstip.com/deploy-react-app-to-aws-fargate-part-01-637c46bd4116
