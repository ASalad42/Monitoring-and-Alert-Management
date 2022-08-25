# Monitoring and Alert Management




![image](https://user-images.githubusercontent.com/104793540/186613020-0d26f8f4-d5f3-44f5-a691-5678a0c573be.png)

![image](https://user-images.githubusercontent.com/104793540/186613095-0af794a2-038c-4244-81de-7bc3702023c7.png)

DevOps monitoring entails overseeing the entire development process from planning, development, integration and testing, deployment, and operations. It involves a complete and real-time view of the status of applications, services, and infrastructure in the production environment. 

DevOps teams should embrace incidents and have high-quality monitors in place to respond to them. Some of the best practices to help with this are:

- Build a culture of collaboration, where monitoring is used during development along with feature/functionality and automated tests
- During development, build appropriate, high-quality alerts in the code that minimize mean time to detect (MTTD) and mean time to isolate (MTTI)
- Build monitors to ensure dependent services operate as expected
- Allocate time to build required dashboards and train team members to use them

#### What is Monitoring and benefits  

Cloud monitoring is a method of reviewing, observing, and managing the operational workflow in a cloud-based IT infrastructure. Manual or automated management techniques confirm the availability and performance of websites, servers, applications, and other cloud infrastructure. This continuous evaluation of resource levels, server response times, and speed predicts possible vulnerability to future issues before they arise.

- Improving the security of cloud applications and networks
- Simple scaling in the event cloud activity increases
- Achieving and maintaining ideal application performance
- Optimizing service availability thanks to rapid issue reporting and rapid resolutions

#### Why should we monitor:
- Frequent code changes demand visibility
- Automated collaboration
- Change management
- Fixing network issues and other problems
- Maintaining availability and security of the services


#### What are the 4 GOLDAN SIGNALS/RULES/AREAS that should be monitored at least:
The four golden signals of monitoring are latency, traffic, errors, and saturation. If you can only measure four metrics of your user-facing system, focus on these four.

- latency 
- traffic
- errors
- saturation 

https://sre.google/sre-book/monitoring-distributed-systems/

#### What is Cloudwatch

CloudWatch provides you with data and actionable insights to monitor your applications, respond to system-wide performance changes, and optimize resource utilization. CloudWatch collects monitoring and operational data in the form of logs, metrics, and events.

Amazon CloudWatch is a monitoring and observability service built for:
- DevOps engineers 
- developers 
- site reliability engineers (SREs) 
- IT managers, and product owners. 

You get a unified view of operational health and gain complete visibility of your AWS resources, applications, and services running on AWS and on-premises. You can use CloudWatch to detect anomalous behavior in your environments, set alarms, visualize logs and metrics side by side, take automated actions, troubleshoot issues, and discover insights to keep your applications running smoothly.

#### What is Alert Management - use cases?
As alerts generate, you can view more information about them, acknowledge them, and take action to resolve them.
use cases:
- a
- b
- c

#### What actions to be taken in case of Alert
You can respond to an alert in the following ways:
- Manually remediate the alert.
- Acknowledge an alert that requires attention.
- Create an incident or security incident.
- Create a case.
- Close the alert.
- Resolve any incident that is related to the alert.
- Reopen the alert.

#### What is SNS - Simple Notification Service
SNS stands for Simple Notification Service. SNS is a fast, flexible fully managed push notification service. as it is a web service that coordinates and manages the delivery and sending of messages to subscribing endpoints or clients. It allows for sending an individual message or fan-out message to a large number of recipients or to other distributed was services.

#### What is SQS
Amazon Simple Queue Service (SQS) is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications.
benefits:
- Eliminate administrative overhead
- Reliably deliver messages
- Keep sensitive data secure


#### Diagram for Monitoring your ec2 instance (include alert management in your diagram)

![image](https://user-images.githubusercontent.com/104793540/186397871-6b564d05-028d-4e84-9426-58fcc8b05d48.png)
https://aws.amazon.com/blogs/security/how-to-monitor-host-based-intrusion-detection-system-alerts-on-amazon-ec2-instances/

![image](https://user-images.githubusercontent.com/104793540/186398302-02d6e078-c909-4bf3-8b37-c7efe41ab800.png)
https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/using-cloudwatch-createalarm.html

My Own:



Documentation:

![image](https://user-images.githubusercontent.com/104793540/186406597-c461de4f-66b6-4170-838e-63c29ea3364d.png)

![image](https://user-images.githubusercontent.com/104793540/186406031-126dc79b-cd8e-4ce6-a577-4356dc1314f5.png)

![image](https://user-images.githubusercontent.com/104793540/186423898-6eee0b30-8b73-46a2-b240-438db80e6b86.png)

![image](https://user-images.githubusercontent.com/104793540/186430201-44f7ee6a-8979-4e50-a54e-39d1397ff344.png)

![image](https://user-images.githubusercontent.com/104793540/186430323-632d96b6-51f1-4f87-baef-d54b17df0130.png)

![image](https://user-images.githubusercontent.com/104793540/186430534-3dd50f74-72b2-4a3a-8c60-fd3e6c403bb2.png)

![image](https://user-images.githubusercontent.com/104793540/186427451-5b207a4d-a175-4856-a846-9acdf01ee863.png)

![image](https://user-images.githubusercontent.com/104793540/186427035-5c88b3c1-c868-4ca3-8ab8-5e57cf784153.png)


![image](https://user-images.githubusercontent.com/104793540/186429892-f6a03ff1-dd5e-4df4-a3ee-41f558ace187.png)


### Logs


Open the CloudWatch console at https://console.aws.amazon.com/cloudwatch/.

In the navigation pane, choose Log groups.

![image](https://user-images.githubusercontent.com/104793540/186606269-e29369b9-f432-442f-86d6-9d93314c6666.png)

On the Log Groups screen, choose the name of the log group.

![image](https://user-images.githubusercontent.com/104793540/186606514-34abd509-215f-46e6-a892-41351fadc2ba.png)

Choose Actions, Export data to Amazon S3.

![image](https://user-images.githubusercontent.com/104793540/186606762-654d2ad1-3086-4aab-9786-d1716482f290.png)

![image](https://user-images.githubusercontent.com/104793540/186617610-c3acea7f-bda0-46bd-bcb9-208c1732cf3d.png)

- To install and configure CloudWatch Logs on an existing Ubuntu Server, CentOS, or Red Hat instance
- Connect to your EC2 instance
- Run the CloudWatch Logs agent installer using one of two options. You can run it directly from the internet, or download the files and run it standalone.
- ![image](https://user-images.githubusercontent.com/104793540/186619375-8f1a45eb-69ea-4971-aca9-2eaf277ea6c9.png)
https://docs.aws.amazon.com/AmazonCloudWatch/latest/logs/QuickStartEC2Instance.html

![image](https://user-images.githubusercontent.com/104793540/186619561-6ba4c0d5-d3ad-4781-9611-0cebdc2f9424.png)


![image](https://user-images.githubusercontent.com/104793540/186617734-1f96007d-6b07-497d-8c0e-6d38cbde6416.png)


On the Export data to Amazon S3 screen, under Define data export, set the time range for the data to export using From and To.

![image](https://user-images.githubusercontent.com/104793540/186607237-0925e33d-592c-4c5a-a31b-f54b5b14c783.png)

s3 bucket prefix > ayanle-log (from s3 policy)

Choose Export to export your log data to Amazon S3.

![image](https://user-images.githubusercontent.com/104793540/186614615-37adc4c6-2ecd-43db-851c-52defb4ac529.png)

- Set permissions on an Amazon S3 bucket (https://docs.aws.amazon.com/AmazonCloudWatch/latest/logs/S3ExportTasksConsole.html)
- In the Amazon S3 console, choose the bucket that you created in step 1.
- Choose Permissions, Bucket policy.
- In the Bucket Policy Editor, add one of the following policies. Change my-exported-logs to the name of your S3 bucket and random-string
- 
```
{
    "Version": "2012-10-17",
    "Statement": [
      {
          "Action": "s3:GetBucketAcl",
          "Effect": "Allow",
          "Resource": "arn:aws:s3:::eng122-ayanle-boto3-bucket",
          "Principal": { "Service": "logs.eu-west-1.amazonaws.com" }
      },
      {
          "Action": "s3:PutObject" ,
          "Effect": "Allow",
          "Resource": "arn:aws:s3:::eng122-ayanle-boto3-bucket/ayanle-log/*",
          "Condition": { "StringEquals": { "s3:x-amz-acl": "bucket-owner-full-control" } },
          "Principal": { "Service": "logs.eu-west-1.amazonaws.com" }
      }
    ]
} 
```

![image](https://user-images.githubusercontent.com/104793540/186626667-83d5f97f-66af-4d20-a13a-074147698c58.png)

To view the status of the log data that you exported to Amazon S3, choose Actions and then View all exports to Amazon S3.

![image](https://user-images.githubusercontent.com/104793540/186627394-82816aad-d9cf-460f-b8ba-1fccdc37b367.png)

https://eng122-ayanle-boto3-bucket.s3.eu-west-1.amazonaws.com/ayanle-log/dd75c944-3af9-497a-b442-50a26233d932/i-093aecf17bf771f5c/000000.gz



## Autoscaling and load balancer

![image](https://user-images.githubusercontent.com/104793540/186675351-2cec10a9-2868-4b2b-8ac9-a0bd0551d8aa.png)
 
Diagram of my architecture explaining steps and functionality of ALB -ASG - TG - Multi- AZs deployment



![image](https://user-images.githubusercontent.com/104793540/186645511-810feced-32b6-471c-a9ba-ab684bb591ec.png)
![image](https://user-images.githubusercontent.com/104793540/186645544-ab9dea3e-0ec8-438e-b06e-3c3676666ca6.png)
![image](https://user-images.githubusercontent.com/104793540/186645852-7eaf2dca-b91a-49e8-9da7-4a5ae3313028.png)
![image](https://user-images.githubusercontent.com/104793540/186646249-f55cd730-845a-4aee-862d-bf16e3556068.png)
![image](https://user-images.githubusercontent.com/104793540/186646325-a693b20c-4587-457b-b076-eacbc8340733.png)
![image](https://user-images.githubusercontent.com/104793540/186646812-b7bda242-fc84-48a3-a687-440414cb12f9.png)


highly available 
![image](https://user-images.githubusercontent.com/104793540/186648963-a8a4fbbf-7007-4d4e-8273-714a81df638c.png)
![image](https://user-images.githubusercontent.com/104793540/186663691-9fd4449e-e78b-460e-bb85-06dc39c1ab01.png)

create an autoscaling group with min 2, desired 2 max 3 - based on cpu usage 40%:
![image](https://user-images.githubusercontent.com/104793540/186688879-197d58d2-8271-48fb-a580-3e4bb77911a4.png)
![image](https://user-images.githubusercontent.com/104793540/186689668-6c2798a0-8e0d-434f-82d8-d6bbff3d8cc1.png)
![image](https://user-images.githubusercontent.com/104793540/186690007-10f31dc9-5b7c-48c6-a4e2-d51500bcd01d.png)
![image](https://user-images.githubusercontent.com/104793540/186691684-f302c843-2b7f-405e-b03f-3fcf1cf15451.png)
![image](https://user-images.githubusercontent.com/104793540/186691927-e41755f3-faf9-4259-a062-911865573d29.png)
![image](https://user-images.githubusercontent.com/104793540/186692021-e58976c0-1a65-4288-ab94-9d6e2a89e5ec.png)

storing logs for asg instance in s3:


Debugging npm for ami before asg:
https://unixcop.com/how-to-create-a-systemd-service-in-linux/
https://docs.aws.amazon.com/autoscaling/ec2/userguide/what-is-amazon-ec2-auto-scaling.html

- You can find running linux service under path /etc/systemd/system
- `cd /etc/systemd/system`
- `sudo nano npm.service`
- add the following:
- 
```
[Unit]
Description=running npm app

[Service]
User=ubuntu
WorkingDirectory=/home/ubuntu/deployment/app
ExecStart=/usr/bin/npm start
Restart=always

[Install]
WantedBy=multi-user.target
```

- `sudo systemctl daemon-reload`
- `sudo systemctl start npm.service`
- `sudo systemctl status npm.service`
- `sudo systemctl enable npm.service`

![image](https://user-images.githubusercontent.com/104793540/186716710-f75f542c-1ebb-453b-b2cc-c1a8dc6785cd.png)

- create ami of this now
- launch template from that 
- auto scale 
- 
