# Aws_Cloud_Tasks

## Deployed Rengo Backend Server

### Task 1
1. Selected the region where the Application was to be deployed.
2. Created a ECS Cluster(Elastic Container Service).
3. Created a Task Definition for the service.
4. Created A ECS_Task_Role with following roles given to it: <br/>
<ul>
<li> AmazonEC2FullAccess (Provides full access to Amazon EC2 via the AWS Management Console.) </li>
<li> AmazonEC2ContainerRegistryFullAccess	(Provides administrative access to Amazon ECR resources.) </li>
<li> AmazonEC2ContainerServiceEventsRole (Policy to enable CloudWatch Events for EC2 Container Service.) </li>
<li> AmazonEC2ContainerServiceforEC2Role	(Default policy for the Amazon EC2 Role for Amazon EC2 Container Service.) </li>
<li> AmazonElasticContainerRegistryPublicFullAccess (Provides administrative access to Amazon ECR Public resources.) </li>
</ul>

5. Created a service using the task Definition.
6. Created a Private ECR.
7. Created a RDS for Database
