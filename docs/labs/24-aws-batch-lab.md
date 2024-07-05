# AWS Batch

1. Create a AWS Resource where your batch jobs will operate

![alt text](images/batch-1.png)

2. Create a new compute environment

![alt text](images/batch-2.png)

3. Select the required network configuration

![alt text](images/batch-3.png)


4. Once the resources are created, now we have to create a job queue

![alt text](images/batch-4.png)

5. Now you can create a job description

![alt text](images/batch-5.png)

![alt text](images/batch-6.png)

![alt text](images/batch-7.png)


Note, you need an execution role

![alt text](images/batch-8.png)

with the following policy

```json

{
	"Version": "2012-10-17",
	"Statement": [
		{
			"Effect": "Allow",
			"Principal": {
				"Service": "ecs-tasks.amazonaws.com"
			},
			"Action": "sts:AssumeRole"
		}
	]
}


```

6. Now you can create the job

![alt text](images/batch-9.png)