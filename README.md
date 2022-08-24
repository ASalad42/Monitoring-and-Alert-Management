# Monitoring and Alert Management

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

![image](https://user-images.githubusercontent.com/104793540/186427035-5c88b3c1-c868-4ca3-8ab8-5e57cf784153.png)

![image](https://user-images.githubusercontent.com/104793540/186430201-44f7ee6a-8979-4e50-a54e-39d1397ff344.png)

![image](https://user-images.githubusercontent.com/104793540/186430323-632d96b6-51f1-4f87-baef-d54b17df0130.png)

![image](https://user-images.githubusercontent.com/104793540/186430534-3dd50f74-72b2-4a3a-8c60-fd3e6c403bb2.png)

![image](https://user-images.githubusercontent.com/104793540/186427451-5b207a4d-a175-4856-a846-9acdf01ee863.png)

![image](https://user-images.githubusercontent.com/104793540/186423898-6eee0b30-8b73-46a2-b240-438db80e6b86.png)

![image](https://user-images.githubusercontent.com/104793540/186429892-f6a03ff1-dd5e-4df4-a3ee-41f558ace187.png)



