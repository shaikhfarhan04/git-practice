Q1: "Tell me something about yourself"





Good morning, and thank you for giving me this opportunity to introduce myself.

I am originally from Ahilyanagar, Maharashtra, and I have been working in the IT industry in Pune for around eight years.



I started my career at Convergys, where I worked as a Technical Support Engineer supporting Dell peripherals. My responsibilities included troubleshooting technical issues, identifying root causes, and providing appropriate solutions to customers.



After that, I joined Birlasoft, where I worked in application and infrastructure support. I supported internal applications, hardware-related issues, and client infrastructure, while coordinating with different technical teams to resolve incidents.



During my time at Birlasoft, I developed an interest in cloud computing and DevOps, so I started upskilling in AWS and related technologies. I also got an opportunity to work closely with DevOps engineers on AWS infrastructure activities.



My exposure included working with AWS services such as EC2, S3, IAM, and Elastic Load Balancing, along with Terraform for infrastructure provisioning. I also gained experience with infrastructure troubleshooting and cloud support activities.



More recently, I have continued developing my practical skills in AWS, Terraform, Linux, Jenkins, and Docker through hands-on projects.



Now, I am looking for an AWS Cloud Engineer opportunity where I can apply my infrastructure support experience, strengthen my cloud engineering skills, and contribute to building and maintaining reliable AWS environments.



=================================================================



Q2: "What is Terraform and use of it?"





Terraform is an open-source Infrastructure as Code tool developed by HashiCorp. It allows us to define, provision, and manage cloud infrastructure using configuration files.



Terraform follows a declarative approach, which means we define the desired state of our infrastructure, and Terraform determines the actions required to achieve that state.



To create an EC2 instance on AWS, I follow these steps.



First, I configure the AWS provider and specify the required AWS region.



Second, I create a Terraform configuration file in which I define the EC2 instance resource, including the AMI ID, instance type, and other required parameters.



Third, I run `terraform init` to initialize the working directory and download the required provider plugins.



Next, I run `terraform fmt` to format the configuration and `terraform validate` to check its syntax and configuration.



Then, I execute `terraform plan` to review the proposed infrastructure changes before applying them.



After reviewing the plan, I run `terraform apply` to provision the EC2 instance.



Finally, I verify the instance using the AWS Management Console or the AWS CLI command `aws ec2 describe-instances`.



This process helps me provision infrastructure in a repeatable, consistent, and manageable way.





==================================================================



Q3 : "An EC2 instance is showing as Running in the AWS Management Console, but you are unable to connect to it through SSH. The instance is running Amazon Linux.



How would you troubleshoot this issue, and what steps would you take to restore SSH connectivity?"

