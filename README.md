# AWS-Deployment-EC2-RDS-S3-Integration

Steps taken:
1. Create EC Instance with Ubuntu AMI.
2. Created Amazon RDS.
3. Created S3 Bucket  to store files into it.
4. Connect RDS using Sqlectron (DB client for Relational DB).
5. Write python script and store it into EC2 Instance


Details:
1. EC2 Instance Setup:
Created an EC2 Instance with Ubuntu AMI.
Installed all required packages and libraries for the project.

2. Amazon RDS Configuration:
Created an Amazon RDS instance named "My Project DB" with specified storage and IOPS.
Connected RDS using Sqlectron, providing necessary details like name, database type, server address, username, and password.

3. Database Management:
Queried the "My Project DB" database.
Created a schema for the "employee" table to store employee information.

4. Python Script Development:
Developed a Python script on the Ubuntu machine.

5. Enabled functionalities like:
Employee data collection and storage through a web interface.
Persistence of data in MySQL database.
Integration with Amazon S3 for efficient storage and retrieval of employee images.
Generation of image URLs for easy viewing.
Provision of user feedback with confirmation pages.

6. Configuration Script:
Developed another Python script containing configurations for AWS services, including RDS endpoint, username, password, database name, S3 bucket, and AWS region.

7. Deployment and Access:
Ran the Python script on the Ubuntu machine.
Accessed the website using the public IP of the Ubuntu machine.

8. Functionality Testing:
Successfully stored employee data in RDS.
Stored images in the S3 bucket via the web interface.
Your project demonstrates a comprehensive setup involving EC2, RDS, and S3, along with efficient scripting for enhanced functionality and user experience. 
