AWS Mini-Projects Portfolio

Hi, I'm Aanand M, and this repository showcases my hands-on mini-projects built while learning and practicing AWS Cloud services.
Each project focuses on a specific AWS service or combination of services, demonstrating real-world skills in deploying, automating, and scaling applications on AWS.

Projects Completed

1. EC2 (Elastic Compute Cloud)

Launched and configured Ubuntu-based EC2 instances.

Hosted a static website on EC2 servers.

Set up security groups and SSH access.


2. IAM (Identity and Access Management)

Created multiple IAM users, groups, roles, and policies.

Practiced security best practices like least privilege access.


3. AMI (Amazon Machine Image)

Created custom AMIs and launch templates for faster EC2 deployment.


4. S3 (Simple Storage Service)

Configured S3 buckets for object storage.

Enabled bucket versioning and hosted a static website using S3.


5. Lambda

Built serverless functions triggered by S3 object uploads.

Connected Lambda with SNS to send email notifications on new uploads.


6. SNS (Simple Notification Service)

Set up SNS topics and subscriptions for event notifications.


7. CloudWatch

Monitored AWS resources and configured alarms for EC2 instance metrics.


8. VPC (Virtual Private Cloud)

Created custom VPC with public and private subnets.

Launched instances in private subnets accessible via a bastion (jump) server in the public subnet.


9. Load Balancer & Auto Scaling

Configured Application Load Balancers.

Set up Auto Scaling Groups triggered by CPU usage to maintain application availability.


10. Elastic Beanstalk

Deployed a static website using AWS Elastic Beanstalk environment for simplified application management.

11. RDS Database Setup and EC2 Connection

Services Used: RDS, EC2

What I Did:

Created a MySQL database in RDS.

Launched an EC2 instance and connected it to the RDS database.

Created tables, inserted data, and took a database dump, storing it back into the EC2.


Why:

To learn managed database services, network security (DB accessibility), and data backup techniques.



Major AWS Project:
Dynamic Website Hosting with EC2 and RDS

Overview

This project involved building a dynamic login-based website hosted on an EC2 instance, with user authentication handled via a backend MySQL database on RDS. It was my first major AWS deployment combining multiple services and full-stack integration.

Tech Stack

Frontend: HTML, PHP

Backend: MySQL (RDS)

Hosting: EC2 (Ubuntu)

AWS Services Used: EC2, RDS, IAM, Security Groups


Steps I Took

1. Launched an EC2 Ubuntu instance and installed Apache, PHP, and MySQL client.


2. Cloned static website files from GitHub and set up the initial web server.


3. Created an RDS MySQL instance and configured security groups to allow EC2 access.


4. Uploaded PHP scripts to EC2 and connected them to the RDS database.


5. Created a login table in MySQL and inserted sample credentials.


6. Debugged missing PHP and MySQL modules until the site was fully functional.



Outcome

Successfully deployed a working login system hosted on EC2 and backed by RDS—all within the AWS Free Tier. This project taught me real-world troubleshooting, multi-service integration, and basic full-stack deployment using AWS.

---

Why These Projects?

Learning AWS is not just about theory — it’s about practical application.
These mini-projects simulate real-world tasks like hosting applications, automating infrastructure, and managing scaling, all critical for cloud-based roles like DevOps Engineer, Cloud Engineer, or Solutions Architect.

Each project helped reinforce:

Service connectivity and security

Automation and scalability

Monitoring and cost optimization

Real-world troubleshooting



---

Technologies Used

AWS EC2, S3, Lambda, SNS, CloudWatch, VPC, Load Balancer, Auto Scaling, Elastic Beanstalk,RDS

Ubuntu Linux

Boto3 (AWS SDK for Python)

Basic HTML/CSS for static websites



---

Next Steps

Currently planning to work on:

Route 53 (DNS Service)



Stay tuned for updates!

Contact

Linkedin: https://www.linkedin.com/in/aanand-m-36b75526b

GitHub: github.com/mrgoose08

