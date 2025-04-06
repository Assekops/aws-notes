AWS Computing Services.
The following are AWS Compute services.
Amazon EC2: Amazon Elastic Copmute Cloud is a web service that provides secure resizable compute capacity in the cloud.

AWS Lambda: is a serverles compute service that helps you run code without provisioning or managing servers. you pay only for the compute time you consume, and you incure no charges when your code isn't running.

Amazon ECS: Amazon Elastic Container Service is a highely scalable and high-performance container management system. It helps customers create new containers and manage them across EC2 instances.

Amazon EKS: Amazon Elastic Kubernetes Service provides the flexibility to start, run and scale kubernetes applications in the cloud or on premises.

AWS Fargate: is a serverless compute engine for containers. It supports both Amazon ECS and Amazon EKS architectures.

AWS Elastic Beanstalk: is an easy to use service for deploying and scaling web applications. You can upload your code, and Elastic Beanstalk automatically handles the deployment, from capacity provisioning, load balancing, auto-scaling to application health monitoring.

![AWS Compute](./diagrams/AWS%20computing%20services.png)

Instance Categories

![AWS Compute](https://github.com/Assekops/aws-notes/blob/main/diagrams/Instance%20categories.png)
-General Purpose
Provide balance of compute, memory and networking resources.
Use case: Ideal for applications that use resources in equal proportion, such as web servers and code repository.

-Compute Optimized
Ideal for compute bound applications that benefit from high performance processors.
Use cases: Batch processing workloads, media transcoding, machine learning interface, and other compute-intensive applications.

-Memory Optimized
Designed to deliver fast performance for workloads that process large datasets in memory.

-Accelerated Computing
Use hardware accelerator, or co-processors, to perform functions such as floating-point calculation, graphical processing, or data pattern matching.

-Storage Optimized
Designed for workloads that require high, sequencial read and write access to very large data sets on local storage. They are optimized to deliver tens of thousands of IOPS to applications.

Vertical Scaling.
![AWS Compute](https://github.com/Assekops/aws-notes/blob/main/diagrams/vertical%20scaling.png)

Vertical Scaling gives an option to changing your instance type. You can scale up or down, as needed, for computing power, memory, disk space and more.

Steps to vertically scale.

1. Stop the instance.
2. Make the desired change to the instance size or type( Scale up or down).
3. Start the instance.

Disadvantages:
-Manual process (but can be automated by using AWS Lambda)
-challenging when you have multiple instances to manage.
-Limited on instance scalability.
-Requires the instance to be unavailable while making changes.

Horizontal Scaling.
![AWS Compute](https://github.com/Assekops/aws-notes/blob/main/diagrams/horizontal%20scaling.png)

Horizontal Scaling is the process of adding or removing EC2 instances depending on the traffic demands.
Benefits:
-Improve fault tolerance.
-Increase application availability.
-Lower costs.
-Requires no downtime to implement.

Amazon EC2 Auto Scaling
-Helps maintain application availability and lets you automatically add or remove EC2 instances according to conditions that you define.
-Launches and terminates instances based on specific conditions.
-Automatically register new instances with load balancers when specified.
-can launch instances across availability zones.
-Replaces unhealthy or unreachable instances with new instances.
-Helps to save money by automating the number of instances based on condition needs.
