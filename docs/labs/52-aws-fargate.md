# ECS Fargate

1. Create an ECS Cluster, make sure you create a cluster by selecting `AWS Fargate`

![alt text](images/fargate-1.png)

2. If you need to collect container logs in CloudWatch, you can configure the cluster to collect them


![alt text](images/fargate-2.png)

3. Select encryption for prod level clusters and make sure you have the `ecs:TagResource` permission to the roles who want to create tasks if the tagging is enabled in the cluster


![alt text](images/fargate-3.png)


4. Create a `task definition`

![alt text](images/fargate-4.png)

5. Select the `arch` type, CPU/Memory configuration

![alt text](images/fargate-5.png)


![alt text](images/fargate-6.png)

6. Configure the container

![alt text](images/fargate-7.png)

![alt text](images/fargate-8.png)

![alt text](images/fargate-9.png)

6. Create a `service`

![alt text](images/fargate-10.png)

7. Select the compute type, we are going to select Launch type as Fargate

![alt text](images/fargate-11.png)
![alt text](images/fargate-12.png)


8. Create the Task

![alt text](images/fargate-13.png)

8. Have the IP configuration

![alt text](images/fargate-14.png)

9. The task will spin up

![alt text](images/fargate-15.png)

![alt text](images/fargate-16.png)

10. Check the webpage

11. To cleanup delete the cluster, service, task and the task definition
