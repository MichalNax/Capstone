# Capstone
Capstone Project


**Introduction:**

In this blog post, we'll walk through the process of completing the AWS Cloud Architecting Capstone project in a non-technical-friendly manner. This guide will provide step-by-step instructions to create a secure and highly available solution.

_Step 0: Inspect the Architecture_

Inspect the example VPC, subnets, security groups, and the AMI.

_Step 1: Create a Cloud9 IDE_

**Note: it is not necessary to make a Cloud9 instance with an Amazon Linux 2 EC2 instance as we are provided a launch template (ExampleLT) with all the necessary resources files on it (the SQL file and Example.zip), so we can skip steps 1-3 HOWEVER it would be a good idea to gain a more comprehensive understanding 

_Step 2: Get the Project Assets_

Clone the repository or download the Example.zip file.
Extract the files to the Apache www folder.

_Step 3: Install a LAMP Web Server on Amazon Linux 2_

Update packages and install the LAMP stack.
Install and start the Apache HTTP server.
Open port 80 from the security group of the Cloud9 EC2 instance.
Get the Cloud9 EC2 public instance IP address and test that you can access the website.

_Step 4: Create a MySQL RDS Database Instance_

Create a db subnet group with the provided specifications.
Create a MySQL RDS database instance with the provided specifications.

_Step 5: Create an Application Load Balancer_

Create a target group.
Create an auto-scaling group.
Launch web instances in the private subnet.

_Step 6: Import the Data into the RDS Database_

Import the data into the RDS database instance from Cloud9 or by accessing the web instance via the bastion host.
Get the SQL dump file.
Connect to the RDS database.
Test that you can access the RDS database.
Import the data into the RDS database.
Test the Application Load Balancer.
Test that the data was imported.

_Step 7: Configure the System Parameters in Parameter Store Systems Manager_

Add the required parameters to the Parameter Store and set the correct values.

**Conclusion:**

Following these steps, you can successfully complete the AWS Cloud Architecting Capstone project, implementing a secure and highly available solution for hosting a website and MySQL database. This comprehensive guide will help beginners gain hands-on experience with AWS services such as EC2 instances, Load Balancers, Amazon RDS, and MySQL databases, while consolidating their skills and knowledge in a practical scenario.

Happy cloud journey, and thank you for reading!
