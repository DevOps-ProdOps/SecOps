AWS (Amazon Web Services) provide robust cloud platform to host your application, infrastructure but security is is something you got to take care of yourself.

There are many incidents where attacker hacks the AWS account and abuse it for their purpose or just for fun.

For example – I came across this post on Quora where user’s AWS account was hacked and received $50,000 bill.

A single sensitive information leakage can cost you heavily and damage the reputation.

So how do you ensure you’ve taken all the necessary steps to protect AWS account?

One way you can do is to follow industry security guidelines manually which is time-consuming and prone to human error.

Or you can use the following SaaS (Software-as-a-service) to automatically audit your AWS platform for the security loophole and misconfiguration.

Note: Below vulnerability scanner are specifically for AWS Cloud and not for website or web applications.

Let’s explore what options we have…

AWS Security Scanners

1. Alien Vault
2. CloudSploit
3. Evident
4. Threat Stack
5. Detectify
6. Skyhigh
7. Qualys
8. Scout2
9. Alert Logic
10. AWS Trusted Advisor
11. Security Monkey
1. Alien Vault
Alien Vault USM (Unified Security Management), one of the market leaders in SIEM (Security Information and Event management) solution for AWS.

USM is a single security monitoring platform to provide visibility of what’s happening so you can take full control of AWS cloud and manage risk.



Some of the essential inbuilt features are:

Monitoring & alerting for S3 & ELB logs, CloudTrail, File integrity, VPC flow
Event correlation
Asset discovery using network, API, software & service
Vulnerability scanning for network, cloud & infrastructure
Intrusion detection for cloud, network, host
Alien Vault provides actionable threat intelligence which is powered by OTX (Open threat intelligence). It works with Amazon shared responsibility model.

With the help of AWS-native sensors, you can detect whenever suspicious instance provisioned, new user, get created, security group modified, etc.

Alien Vault offers 14 days FREE trial.

2. CloudSploit
CloudSploit is capable of detecting hundreds of threats in AWS account by automated security scanning and configuration monitoring.



You can use CloudSploit in every AWS regions, and it’s not just provide scanning results but also the recommendation to fix the issues.



CloudSploit offer API which is useful if you are looking to integrate security scanning in your application. A good thing is you don’t need to install any agent on your server to be monitored.

You can get it started in FREE for unlimited on-demand scans. And if you are looking for an automated scan, risk finding emails, real-time event streams, etc. then you got to pay for it.

3. Evident
Evident let you see what’s happening in your AWS account in all the regions and services. Evident checks against more than 100 security best practice to detect changes in real-time.

If you are looking to make your cloud environment compliant with SOC 2, HIPPA, FedRAMP, PCI, ISO 27001 then compliance assessment &  reporting is easy with Evident.

4. Threat Stack
Threat Stack platform scan and let you monitor multiple AWS accounts in a central dashboard. Compare the security policies with AWS best and industry benchmark for EC2, IAM, RDS, and S3.



Scheduling scan and integrating the alerting with Slack, PagerDuty is possible.

By integrating with CloudTrail, you can have full visibility and be notified of unauthorized changes in AWS resources.

5. Detectify
Detectify is known for finding web application vulnerability, but recently they have included S3 misconfiguration scanning. So if you are using AWS just for S3 and need web application + S3 security checks, then you can leverage Detectify.



As I write, Detectify checks the following six types of vulnerabilities in AWS S3.

Full anonymous access
Arbitrary file listing
Blind uploads
Arbitrary file upload and exposures
ACL/PCL information leakage
Arbitrary read/write of objects
6. Skyhigh
Skyhigh, provide comprehensive security monitoring, auditing, compliance, and remediation for AWS infrastructure.



Some of the essential features of Skyhigh are:

Complete audit trail of users activity
Detect insider threats, compromised accounts
Compliance, user permission and security configuration auditing
Enforce data loss prevention policies
Cloud activity monitoring
IAM, account access, user behavior analytics
Integration with SIEM and IDM
Multi-tier remediation
It supports a forensic investigation and automatically includes threats resolution data into self-learning for improved detection accuracy.

7. Qualys
Qualys, one of the industry leaders in vulnerability scanner platform for website, network provide total visibility of AWS cloud to secure and compile from internal and external policies.

Qualys provides cloud agent which can be installed either on EC2 or at the source into AMI for automated asset discovery, classification, monitoring, and vulnerability remediation.

8. Scout2
Scount2 is a python based open-source tool to view the security posture of AWS environment. Scout2 python script fetches CloudTrail, S3, AMI, EC2, etc. data and reports it in HTML format.



Risk items are categorized automatically and denoted in danger and warning with red and yellow color respectively.

Scout2 is actively maintained so if you are looking for a free solution then give a try to see if this serve the purpose.

9. Alert Logic
Improve your AWS security posture with Alert Logic Cloud Insight. Alert Logic is capable of inspecting full stack infrastructure including network, open source, enterprise software against more than 92000 known vulnerabilities.



Some of the essential Alert Logic key capabilities are:

Visual topology map for faster prioritization
Remediation prioritization based on severity of vulnerabilities
Track improvement trends
Easy integration with SecOps & DevOps using RESTful API
Agentless comprehensive checks
10. AWS Trusted Advisor
The list won’t be complete without mentioning AWS Trusted Advisor, a real-time guide to improve security, reduce cost by following AWS best practices.



11. Security Monkey
Security Monkey by Netflix is known to work on Ubuntu, Linux & OS X. Get alerted when insecure configuration found in your AWS accounts.



Security Monkey store previous state of the environment and show you what and when got changed for auditing.

AWS provide security on core infrastructure but what you deploy, configure is your responsibility. I hope above listed AWS security scanning solution help you to keep your AWS cloud environment secure & cost effective.

TAGS: AWS

More Great Reading on Geekflare
11 Website Defacement Monitoring Tools for Better Security
Cryptocurrency And Cyber Security – Are they Frenemies?
What is SQL Injection and How to Prevent in PHP Applications?
8 Best Tools to Monitor and Debug Serverless Applications
Joomla Security Scanner to Keep Website Safe and Secure
Secure MIME Types in Apache & Nginx with X-Content-Type-Options
