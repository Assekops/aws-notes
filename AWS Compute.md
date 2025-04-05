Instance Categories
![Amazon Storage](https://github.com/Assekops/aws-notes/blob/main/diagrams/Instance%20categories.png)
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
![Amazon Storage](https://github.com/Assekops/aws-notes/blob/main/diagrams/vertical%20scaling.png)

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
![Amazon Storage](https://github.com/Assekops/aws-notes/blob/main/diagrams/horizontal%20scaling.png)

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
