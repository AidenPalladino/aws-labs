# AWS Labs

Write-ups of three separate AWS Academy labs I did for my cloud computing coursework at USF. Each lab had its own environment and goal, and each folder has its own README with the steps, screenshots, and what I'd change in a real environment.

| Lab | What it covers |
|---|---|
| [VPC and Web Server](VPC-Web-Server/) | Building a VPC with public and private subnets across two Availability Zones, a NAT gateway, and an EC2 web server behind a security group |
| [Security Groups and NACLs](Security-Groups-NACLs/) | Tightening access to a private app server step by step, security group referencing, network ACL rule order, and reaching a private instance through a bastion host and Session Manager |
| [CloudTrail Monitoring](CloudTrail-Monitoring/) | Alerting on security group changes with CloudTrail, EventBridge and SNS, a CloudWatch alarm for repeated failed console logins, and a Logs Insights query to investigate them |

Account IDs, resource IDs, public IPs and email addresses are blacked out in the screenshots.
