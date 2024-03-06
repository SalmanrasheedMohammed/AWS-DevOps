# AWS-DevOps

**AWS**
* Amazon Web Services (AWS) is a leading cloud computing platform that offers a wide range of on-demand services, including computing power, storage, databases, machine learning, and developer tools.
* AWS organizations can quickly scale their infrastructure, reduce costs, and increase agility by accessing resources on a pay-as-you-go basis.
* By offering a secure and reliable cloud infrastructure, AWS allows businesses to focus on their core activities, innovation, and growth, without being bogged down by the complexities and costs of managing hardware or infrastructure.

**Public Cloud**
* Accessibility: Public cloud services are accessible to anyone over the internet. Users can access resources on-demand from anywhere with an internet connection.
* Shared Infrastructure: Resources in a public cloud environment are shared among multiple users and organizations, leading to cost savings through economies of scale.
* Scalability: Public cloud services offer elastic scalability, allowing users to rapidly scale resources up or down based on demand.
* Managed by Third-party: Public cloud infrastructure is owned, managed, and maintained by third-party cloud service providers, relieving users of the burden of hardware management and maintenance tasks.
* Pay-as-you-go Pricing: Public cloud services typically operate on a pay-as-you-go pricing model, where users only pay for the resources they consume, providing cost-efficiency and flexibility.

**Private cloud**
* Dedicated Infrastructure: Private cloud environments are deployed on dedicated infrastructure, either on-premises or in a hosted data center, providing more control and customization options.
* Isolated Environment: Resources in a private cloud are dedicated to a single organization, offering enhanced security and privacy compared to public cloud environments.
* Customization: Private clouds offer greater customization and configuration options, allowing organizations to tailor the infrastructure to their specific needs and compliance requirements.
* Scalability: Private clouds can be scaled, but typically not as rapidly as public clouds due to the need for additional hardware procurement and deployment.
* Ownership and Control: Private cloud infrastructure is owned and operated by the organization itself, providing greater control over security, compliance, and data governance.

**why to use Public cloud?**
- Cost efficiency through pay-as-you-go pricing.
- Elastic scalability to meet changing demand.
- Global reach for improved performance and user experience.
- Reliability with redundant infrastructure and high availability.
- Robust security measures and compliance certifications.
- Access to a wide range of managed services for offloading infrastructure management.
- Foster innovation and agility through access to cutting-edge technologies.
- Ease of use with intuitive interfaces and APIs for resource management.

**IAM**
* IAM stands for Identity and Access Management. It is a core service provided by AWS that allows you to manage access to your AWS resources securely. In brief, IAM enables you to control who can access your AWS resources (authentication) and what actions they can perform (authorization).
    * Users
    * Groups
    * Roles
    * Policies
    * Access Keys
    * Multi-factor Authentication (MFA)

**Create an IAM user in AWS**
* Sign in to the AWS Management Console
* Navigate to IAM
* Access IAM Dashboard
* Click on "Add user"
* Enter user details
* Set permissions
* Review
* Create user
* Access keys (optional)
* Completion
* Copy and paste the creditionals, and login into IAM user.

**EC2**
- An EC2 (Elastic Compute Cloud) instance is a virtual server provided by Amazon Web Services (AWS) within its Elastic Compute Cloud service.
- EC2 instances are the fundamental building blocks of AWS's cloud computing platform. They allow users to rent virtual machines (VMs) for running applications or hosting websites.
- **Keypoints**
   - Elasticity and Scalability.
   - Instance Types: general-purpose, compute-optimized, memory-optimized, storage-optimized, and more.
   - Operating System Support: Users can choose from a variety of operating systems, including various Linux distributions, Microsoft Windows Server, and others.
   - Flexible Pricing: including On-Demand Instances, Reserved Instances, and Spot Instances, allowing users to optimize costs based on their usage patterns.
   - Integration with Other AWS Services: EC2 integrates seamlessly with other AWS services like Amazon EBS (Elastic Block Store), Amazon S3 (Simple Storage Service), Amazon RDS (Relational Database Service), and more, allowing for building complex and scalable architectures.
   - Security and Compliance: EC2 provides features such as Security Groups, Network Access Control Lists (NACLs), and Virtual Private Clouds (VPCs) to ensure secure deployment and isolation of resources.
   - Monitoring and Management: AWS offers tools like Amazon CloudWatch for monitoring EC2 instances' performance and AWS Systems Manager for managing and automating administrative tasks.

**VPC**
- In Amazon Web Services (AWS), a Virtual Private Cloud (VPC) is a foundational networking construct that allows you to provision a logically isolated section of the AWS Cloud where you can launch AWS resources in a virtual network that you define.
- **keypoints**
   - VPC
   - Subnets
   - Internet Gateway (IGW)
   - Route Tables
   - Network Access Control Lists (NACLs)
   - Security Groups

![image](https://github.com/SalmanrasheedMohammed/AWS-DevOps/assets/101308889/980f2a49-a8df-4242-aef7-ac5f03ae5461)

**Route53**
- Amazon Route 53 is a highly scalable and reliable Domain Name System (DNS) web service provided by Amazon Web Services (AWS). It is designed to route end users to applications and resources by translating human-readable domain names into IP addresses.
- map your name with IP address
- --Domain name--load balancer--IP address--Application--
- ![image](https://github.com/SalmanrasheedMohammed/AWS-DevOps/assets/101308889/fa16e017-5aaa-4654-8682-952fb252818f)
   - **Key components**
      - Domain Registration
      - DNS Service
      - Health Checks
      - DNS Failover
      - Traffic Routing Policies
      - Integration with AWS Services
      - Global Network Infrastructure





