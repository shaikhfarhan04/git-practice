# 🎯 AWS Cloud Engineer Mock Interview — Round 1

We'll conduct your mock interview based on your resume, including your AWS Cloud Engineer contract experience, previous Cloud Support Associate role at Birlasoft, and your technical skills in AWS, Linux, Terraform, Jenkins, Docker, and monitoring.

Your resume highlights experience with EC2, S3, VPC, IAM, ELB, CloudWatch, Terraform, Jenkins CI/CD, and Docker. We'll focus on these areas and progressively introduce production-level troubleshooting scenarios. Farhan Shaikh CV - AWS

## How this mock interview will work

I'll act as your technical interviewer.

- **One question at a time:** Answer as you would in a real interview.
- **Honest evaluation:** I'll assess your technical accuracy, clarity, and practical understanding.
- **Score out of 10:** You'll receive a score for each answer.
- **Feedback:** I'll explain what you did well and what you should improve.
- **Model answer:** I'll provide an interview-ready answer after evaluating yours.
- **Increasing difficulty:** We'll progress from HR and fundamentals to hands-on AWS troubleshooting and critical-thinking scenarios.

### Interview roadmap

| Round | Focus | Difficulty |
|---|---|---|
| 1 | Introduction and resume verification | Easy–Medium |
| 2 | AWS fundamentals, EC2, and IAM | Medium |
| 3 | VPC, networking, and security | Medium–Hard |
| 4 | Linux administration and troubleshooting | Medium–Hard |
| 5 | Terraform and Infrastructure as Code | Medium–Hard |
| 6 | Jenkins, CI/CD, and Docker | Medium–Hard |
| 7 | CloudWatch, monitoring, and production support | Hard |
| 8 | Real-world AWS incident scenarios | Hard–Advanced |
| 9 | Architecture and critical thinking | Advanced |
| 10 | Final evaluation and preparation plan | — |

Let's begin. Answer in your own words; don't worry about making mistakes. That's what this practice is for.

---

## 🎤 Question 1: Tell Me About Yourself

**Interviewer:**

"Good morning, Farhan. Please introduce yourself and walk me through your professional experience. I can see from your resume that you have worked in technical support and cloud support and have subsequently focused on AWS Cloud Engineering.

Could you explain your professional journey, your current technical skills, your hands-on experience with AWS and DevOps tools, and why you are looking for an AWS Cloud Engineer position?"

**Your instructions:**
- Imagine we're in a real technical interview.
- Aim for a **60–90-second answer**.
- Explain your experience in your own words.
- Focus on your actual work and projects rather than listing every technology on your resume.

**Your turn:** Type your answer as if you're speaking directly to the interviewer.

I'll evaluate your response out of 10, suggest improvements, and then move to Question 2.

Good start, Farhan! 👍 You have explained your career journey in a logical order, from technical support to application support and then toward AWS Cloud Engineering. You have also mentioned relevant AWS services and Terraform, which are important for this role.

Let's evaluate your answer as if I were the interviewer.

## 1. Mock Interview Evaluation — Question 1

**Question:** Tell me about yourself and walk me through your professional experience.

| Evaluation criteria | Score | Feedback |
|---|---:|---|
| Career introduction | 7/10 | You explained your background and location. |
| Career progression | 8/10 | You showed progression from technical support to cloud engineering. |
| AWS technical knowledge | 7/10 | You mentioned EC2, databases, load balancers, IAM, S3, and Terraform. |
| Communication and grammar | 5/10 | Some sentences were long and could be more professional and structured. |
| Confidence and clarity | 6/10 | The experience is relevant, but you should explain your responsibilities more clearly. |
| **Overall score** | **6.5/10** | Good foundation; improve structure and technical precision. |

### 2. How to improve your answer

Three things will make your introduction stronger:

1. **Explain your career progression clearly.** Start with technical support, move to application and infrastructure support, and then explain how you developed your AWS skills.
2. **Describe your contribution accurately.** Explain what you personally did with Terraform and AWS rather than suggesting that you managed the entire infrastructure if you worked alongside DevOps engineers.
3. **End with your career objective.** Tell the interviewer why you are ready for an AWS Cloud Engineer role.

### 3. Improved interview answer

Here is a polished version based on the experience you described and the details in your resume. Practise speaking naturally rather than memorising every word.

Good morning, and thank you for giving me this opportunity to introduce myself.

I am originally from Ahilyanagar, Maharashtra, and I have been working in the IT industry in Pune for around eight years.

I started my career at Convergys, where I worked as a Technical Support Engineer supporting Dell peripherals. My responsibilities included troubleshooting technical issues, identifying root causes, and providing appropriate solutions to customers.

After that, I joined Birlasoft, where I worked in application and infrastructure support. I supported internal applications, hardware-related issues, and client infrastructure, while coordinating with different technical teams to resolve incidents.

During my time at Birlasoft, I developed an interest in cloud computing and DevOps, so I started upskilling in AWS and related technologies. I also got an opportunity to work closely with DevOps engineers on AWS infrastructure activities.

My exposure included working with AWS services such as EC2, S3, IAM, and Elastic Load Balancing, along with Terraform for infrastructure provisioning. I also gained experience with infrastructure troubleshooting and cloud support activities.

More recently, I have continued developing my practical skills in AWS, Terraform, Linux, Jenkins, and Docker through hands-on projects.

Now, I am looking for an AWS Cloud Engineer opportunity where I can apply my infrastructure support experience, strengthen my cloud engineering skills, and contribute to building and maintaining reliable AWS environments.

**Important:** Keep only the statements you can confidently explain with real examples. If you used Terraform primarily in practice projects rather than in a client environment, distinguish those experiences clearly when the interviewer asks follow-up questions.

---

## 4. Follow-up questions an interviewer might ask

After this introduction, an interviewer may ask:

- What exactly did you do using Terraform?
- Can you explain the AWS infrastructure you worked on?
- How did you configure security groups and IAM policies?
- What is the difference between an EC2 instance and an RDS database?
- Did you create the infrastructure yourself, or did you assist the DevOps team?
- Can you explain one real incident you troubleshot?

You should be ready to answer these with specific examples.

---

# 🎯 Mock Interview — Question 2: AWS and Terraform

**Interviewer:**

“You mentioned that you worked with DevOps engineers and used Terraform to provision AWS infrastructure. Can you explain how Terraform works and walk me through the steps you would follow to create an EC2 instance on AWS using Terraform?”

### Your instructions
Answer as if you are speaking directly to the interviewer. Try to cover:

1. What Terraform is.
2. What Infrastructure as Code means.
3. The basic steps or commands you use to provision infrastructure.
4. How Terraform communicates with AWS.
5. How you verify that the EC2 instance was created successfully.

**Your turn, Farhan.** Answer in your own words. I'll score your answer out of 10, correct any technical mistakes, and help you develop an interview-ready response.

Good attempt, Farhan! 👍 You understand the basic purpose of Terraform, Infrastructure as Code (IaC), and verifying AWS resources using the AWS CLI. Now let's improve your answer to make it suitable for an **AWS Cloud Engineer interview**.

## 1. Mock Interview Evaluation — Question 2

**Question:** What is Terraform, and how would you create and verify an EC2 instance using Terraform?

| Evaluation criteria | Score | Feedback |
|---|---:|---|
| Understanding of Terraform | 8/10 | Correctly identified Terraform as an open-source IaC tool. |
| Understanding of declarative configuration | 7/10 | You mentioned declarative configuration, but could explain it more clearly. |
| Terraform provisioning workflow | 3/10 | You haven't explained the actual provisioning steps and commands. |
| AWS integration | 4/10 | You need to explain how the AWS provider connects Terraform to AWS. |
| Resource verification | 6/10 | AWS CLI is a valid verification method, but your command needs correction. |
| **Overall score** | **5.5/10** | Good fundamentals; focus on practical implementation. |

### 2. Important technical correction

You provided this command:

```bash
aws ec2 describe-instance --instance-ids 09899399sdfjklj
```

The correct AWS CLI command is:

```bash
aws ec2 describe-instances --instance-ids i-0123456789abcdef0
```

**Remember:** The command is `describe-instances`, not `describe-instance`.

Replace the example instance ID with your actual EC2 instance ID.

You can also use:

```bash
aws ec2 describe-instances \
  --instance-ids i-0123456789abcdef0 \
  --query "Reservations[].Instances[].[InstanceId,State.Name,InstanceType]" \
  --output table
```

This displays the instance ID, current state, and instance type.

---

## 3. Interview-ready answer

Here is a stronger answer based on your response.

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

### 4. Remember this Terraform workflow

| Step | Command | Purpose |
|---|---|---|
| 1 | `terraform init` | Initialize Terraform and download providers. |
| 2 | `terraform fmt` | Format Terraform configuration files. |
| 3 | `terraform validate` | Validate configuration syntax and structure. |
| 4 | `terraform plan` | Preview proposed infrastructure changes. |
| 5 | `terraform apply` | Apply the plan and provision resources. |
| 6 | `aws ec2 describe-instances` | Verify the EC2 instance using AWS CLI. |
| 7 | `terraform destroy` | Destroy Terraform-managed resources when appropriate. |

**Interview tip:** Don't say that Terraform automatically creates every resource simply because you write a configuration file. You must initialize the working directory, review the plan, and apply the changes. AWS credentials and permissions must also be configured correctly.

---

# 🎯 Mock Interview — Question 3: EC2 Troubleshooting

Let's move to a practical scenario. This is a common type of question for AWS Cloud Engineer and Cloud Support roles.

**Interviewer:**

"An EC2 instance is showing as `Running` in the AWS Management Console, but you are unable to connect to it through SSH. The instance is running Amazon Linux.

How would you troubleshoot this issue, and what steps would you take to restore SSH connectivity?"

### Your answer should cover
1. What you would check first.
2. How you would verify the security group.
3. How you would check the subnet route table and network ACL.
4. How you would investigate the operating system and SSH service.
5. How you would confirm that connectivity has been restored.

**Your turn, Farhan.** Answer as if you're explaining your troubleshooting process to an interviewer. Don't worry about perfect grammar yet; focus on the technical steps and logical sequence.

Good answer, Farhan! 👍 You're following the correct troubleshooting sequence. You started with the EC2 instance state and health checks, then moved to security groups, routing, network ACLs, and the operating system. That's the right approach for an AWS Cloud Engineer.

Let's evaluate your answer as an interviewer would.

## 1. Mock Interview Evaluation — Question 3

**Scenario:** An Amazon Linux EC2 instance is running, but SSH connectivity is failing.

| Evaluation criteria | Score | Feedback |
|---|---:|---|
| EC2 instance state and health | 9/10 | Correctly started with instance state and health checks. |
| Security group | 9/10 | Correctly identified inbound SSH on TCP port 22. |
| Networking and routing | 8/10 | Mentioned the route table, Internet Gateway, and network ACL. |
| Operating system troubleshooting | 6/10 | You mentioned the OS and SSH service, but need specific checks. |
| SSH client configuration | 8/10 | Correctly mentioned the IP address and username. |
| Troubleshooting sequence | 8/10 | Good logical sequence; add connectivity and authentication checks. |
| **Overall score** | **8/10** | Good answer. Now add practical commands and explain what you would do if each check failed. |

## 2. What you should improve

Your answer identifies the main components, but interviewers often ask, **"How exactly would you check that?"**

For example:

- Instead of saying, "I will check the security group," explain that you would verify inbound TCP port 22 is allowed from your current public IP.
- Instead of saying, "I will investigate the OS," mention checking the SSH service using `systemctl`.
- Instead of saying, "I will check the route table," explain that a publicly accessible instance generally needs a route to an Internet Gateway and a public IP address.

Remember that the correct troubleshooting path depends on whether the instance is public or private. A private EC2 instance generally requires a bastion host, VPN, AWS Systems Manager Session Manager, or another approved access path.

## 3. Interview-ready answer

Here is how you can present your answer in a real interview.

First, I would check the EC2 instance state and confirm that it is running and that both instance status checks and system status checks are passing.

Second, I would verify the security group and confirm that inbound TCP port 22 is allowed from my authorized public IP address.

Third, I would check the subnet's route table. If the instance is intended to be publicly accessible, I would verify that the route table has a route to the Internet Gateway and that the instance has a public IP address.

Next, I would check the network ACL to ensure that SSH traffic and the required return traffic are permitted.

If the network configuration is correct, I would investigate the operating system. I would check whether the SSH service is running, whether the OS firewall is blocking traffic, and whether the SSH configuration is correct. I would also verify the private key, file permissions, username, and destination IP address.

Finally, I would attempt to reconnect using SSH and confirm that the connection is successful. After restoring access, I would document the root cause and the corrective action.

### 4. Practical commands to remember

**Check instance state and status checks:**
```bash
aws ec2 describe-instance-status \
  --instance-ids i-0123456789abcdef0 \
  --include-all-instances
```

**Check SSH service on Amazon Linux**, if you can access the server through an alternative method:
```bash
sudo systemctl status sshd
```

If the service is stopped and you confirm that it should be running:
```bash
sudo systemctl start sshd
```

**Connect using SSH from your local terminal:**
```bash
ssh -i "your-key.pem" ec2-user@YOUR_PUBLIC_IP
```

For Amazon Linux, `ec2-user` is the usual default username.

**Important:** If SSH is unreachable, you cannot run commands on the instance through SSH until access is restored. Use an alternative access method, such as Session Manager, if configured, or investigate through other appropriate recovery methods.

---

# 🎯 Mock Interview — Question 4: AWS VPC Networking

Now let's increase the difficulty slightly.

**Interviewer:**

"You have created an EC2 instance in a public subnet. Its security group allows inbound HTTP traffic on port 80 from `0.0.0.0/0`, and the web server is running. However, users cannot access the website through the instance's public IP address.

How would you troubleshoot this issue?"

### Your turn

Explain your troubleshooting process in order. Consider:

1. Whether the web server is listening on port 80.
2. Whether the EC2 instance has a public IPv4 address.
3. The subnet route table and Internet Gateway.
4. The security group and network ACL.
5. The operating system firewall and web server logs.

**Answer in your own words, as you would in a real interview.** I'll evaluate your answer, give you a score, and help you improve it before moving to the next scenario.

Good answer, Farhan! 👍 Your troubleshooting approach is becoming more structured. You covered the web server, public IP, Internet Gateway, security group, network ACL, operating system firewall, and logs.

One particularly good point is that you mentioned **checking whether Apache or Nginx is running and using `journalctl` to investigate errors**. That demonstrates practical Linux troubleshooting knowledge.

Let's evaluate your answer.

## 1. Mock Interview Evaluation — Question 4

**Scenario:** An EC2 instance has a public IP address and a security group allowing HTTP on port 80, but users cannot access the website.

| Evaluation criteria | Score | Feedback |
|---|---:|---|
| Web server troubleshooting | 9/10 | Correctly identified port 80 and Apache/Nginx status. |
| Public IP verification | 9/10 | Correctly identified the need to check the public IPv4 address. |
| VPC networking | 8/10 | Correctly mentioned the Internet Gateway and route table. |
| Security group and NACL | 9/10 | Correctly included both network security controls. |
| Linux troubleshooting | 9/10 | Good inclusion of the OS firewall and `journalctl`. |
| Troubleshooting sequence | 8/10 | Good overall sequence; add commands and local connectivity tests. |
| **Overall score** | **8.5/10** | Strong answer. Now focus on validating each layer with evidence. |

## 2. What would make your answer even stronger?

An interviewer may follow up with:

**"You checked the web server status, and it shows active. How do you determine whether the application is actually accepting connections?"**

You should test the service from inside the EC2 instance.

### Step 1: Check Apache or Nginx

For Amazon Linux, check Apache:

```bash
sudo systemctl status httpd
```

For Nginx:

```bash
sudo systemctl status nginx
```

Remember that Apache commonly runs as `httpd` on Amazon Linux.

### Step 2: Check whether port 80 is listening

```bash
sudo ss -lntp | grep ':80'
```

This helps determine whether a process is listening on port 80.

### Step 3: Test the website locally

```bash
curl -I http://localhost
```

Interpret the result:

- **HTTP 200:** The web server is responding successfully.
- **HTTP 403:** The server is reachable, but access is forbidden.
- **HTTP 404:** The server responds, but the requested resource is not found.
- **Connection refused:** Nothing is accepting the connection at the tested address and port, or the connection is actively rejected.

These results narrow down the issue, but they do not independently establish the root cause.

### Step 4: Check the logs

For Apache:

```bash
sudo journalctl -u httpd --since "30 minutes ago"
```

For Nginx:

```bash
sudo journalctl -u nginx --since "30 minutes ago"
```

You can also check Apache's error log:

```bash
sudo tail -n 50 /var/log/httpd/error_log
```

For Nginx:

```bash
sudo tail -n 50 /var/log/nginx/error.log
```

### Step 5: Verify the AWS networking

Confirm the following:

1. The EC2 instance has a public IPv4 address.
2. The subnet route table contains `0.0.0.0/0` pointing to an Internet Gateway.
3. The security group allows inbound TCP port 80 from the intended client IP range.
4. The network ACL permits inbound HTTP traffic and the necessary outbound response traffic, including ephemeral destination ports for return traffic.
5. The operating system firewall is not blocking the connection.

**Interview tip:** If `curl http://localhost` succeeds but the public website remains unreachable, focus next on the listening address, public IP, routing, security groups, NACLs, and external connectivity.

---

# 🎯 Mock Interview — Question 5: EC2 CPU Utilization at 95%

Let's move to a production troubleshooting scenario. This tests your ability to investigate a performance incident rather than simply check whether a service is running.

**Interviewer:**

"An EC2 instance hosting a production application suddenly reaches 95% CPU utilization. Users report that the application is responding very slowly. The instance is still running, and you can connect to it through SSH.

How would you investigate the high CPU utilization, identify the root cause, and resolve the issue without unnecessarily restarting the server?"

### Your turn, Farhan

Explain your troubleshooting steps in order. Consider:

1. How you confirm the CPU alarm and determine when the problem started.
2. Which Linux commands you would use to identify the process consuming CPU.
3. How you would distinguish an application issue from a system-level issue.
4. What corrective action you would take.
5. How you would verify recovery and prevent the issue from recurring.

**Answer in your own words, as you would in a real interview.** I'll evaluate your response out of 10 and help you strengthen it.

Good attempt, Farhan! 👍 You're thinking in the right direction. You correctly identified checking CloudWatch alarms, using `ps` and `top` to identify CPU-consuming processes, investigating recent updates, and checking application logs with `journalctl`.

Your next step is to explain **what you would do after identifying the process consuming CPU**. An interviewer wants to see how you move from monitoring to root-cause analysis, remediation, and recovery.

## 1. Mock Interview Evaluation — Question 5

**Scenario:** EC2 CPU utilization reaches 95%, and users report that the application is slow.

| Evaluation criteria | Score | Feedback |
|---|---:|---|
| CloudWatch monitoring | 9/10 | Correctly mentioned the CPU alarm and when the issue started. |
| Linux troubleshooting | 9/10 | `top` and `ps` are appropriate commands. |
| Root-cause investigation | 7/10 | Good start, but explain how you distinguish application and system-level issues. |
| Log analysis | 8/10 | `journalctl` is useful; identify the relevant service and time range. |
| Corrective action | 4/10 | You haven't explained how you would safely resolve the issue. |
| Recovery and prevention | 3/10 | Explain how you would verify recovery and prevent recurrence. |
| **Overall score** | **7/10** | Good troubleshooting fundamentals. Focus on remediation and verification. |

## 2. Improve your practical troubleshooting skills

Imagine you're connected to an Amazon Linux EC2 instance experiencing 95% CPU utilization.

### Step 1: Check CloudWatch

Review the EC2 `CPUUtilization` metric and identify when the increase began.

Check whether the CPU spike coincides with a deployment, scheduled job, traffic increase, or application update.

### Step 2: Identify the process consuming CPU

Run:

```bash
top
```

Look for processes consuming unusually high CPU.

For a sorted process list, use:

```bash
ps -eo pid,ppid,comm,%cpu,%mem --sort=-%cpu | head -15
```

This displays the processes with the highest CPU consumption.

### Step 3: Investigate the process

Suppose the output shows a Java application consuming 90% CPU.

Check its process details:

```bash
ps -fp <PID>
```

Replace `<PID>` with the actual process ID.

Then investigate the relevant application logs:

```bash
sudo journalctl -u <service-name> --since "30 minutes ago"
```

If the application writes logs to its own files, inspect those files as well.

Look for:
- Recent deployments or configuration changes.
- Excessive request volume.
- Repeated errors or retry loops.
- Resource-intensive background jobs.
- Unexpected processes or suspicious activity.

**Important:** High CPU alone doesn't prove that an application is faulty. The cause might be legitimate traffic, inefficient code, a background task, or a system process.

### Step 4: Resolve the issue safely

Choose the corrective action based on the evidence.

| Identified cause | Possible action |
|---|---|
| Application process stuck in a loop | Investigate the code or configuration and restart the service if justified. |
| Unusually high traffic | Investigate request patterns and scale capacity if necessary. |
| Resource-intensive scheduled job | Review the job and adjust its execution schedule or workload. |
| Recent faulty deployment | Roll back the deployment using the approved procedure. |
| Instance capacity insufficient | Evaluate vertical scaling or horizontal scaling. |

Avoid immediately terminating processes or rebooting the instance. Those actions can disrupt production and destroy useful diagnostic evidence.

### Step 5: Verify recovery

After applying the corrective action:

```bash
top
```

Confirm that CPU utilization has returned to an acceptable level.

Also:
- Verify that the application responds correctly.
- Check application and system logs for new errors.
- Confirm that CloudWatch CPU metrics have stabilized.
- Monitor the service to ensure the issue does not recur.

This final step is important because **resolving the immediate symptom is not the same as confirming the root cause has been fixed**.

---

## 3. Interview-ready answer

Here is a polished version you can practise.

First, I would check the CloudWatch CPUUtilization metric to identify when the CPU spike started and correlate it with any recent deployments, traffic increases, or scheduled jobs.

Next, I would connect to the instance through SSH and use the `top` and `ps` commands to identify which process is consuming the most CPU.

Once I identify the process, I would investigate it further and check the relevant application and system logs using `journalctl` or the application's log files. I would look for issues such as an application loop, a resource-intensive job, increased traffic, or a recent configuration change.

Based on the findings, I would take the appropriate corrective action, such as fixing the application issue, rolling back a faulty deployment, or scaling the infrastructure if the existing capacity is insufficient.

Finally, I would monitor CPU utilization in CloudWatch, verify that the application is responding normally, and confirm that the issue does not recur. I would also document the root cause and preventive measures.

---

# 🎯 Mock Interview — Question 6: AWS IAM Troubleshooting

Let's move to an important AWS security scenario.

**Interviewer:**

"An application running on an EC2 instance needs to upload files to an S3 bucket. The application was working yesterday, but today it is failing with the following error:"

```text
An error occurred (AccessDenied) when calling the PutObject operation:
Access Denied
```

"The EC2 instance is running, and the S3 bucket exists. How would you troubleshoot this issue and restore the application's ability to upload files securely?"

### Your turn, Farhan

Explain your troubleshooting approach. Consider:

1. How you would identify which IAM identity the application is using.
2. How you would investigate IAM permissions.
3. Whether the S3 bucket policy could be involved.
4. How you would check for explicit denies or other policy restrictions.
5. How you would resolve the issue without giving unnecessarily broad permissions.

**Answer in your own words.** I'll evaluate your response out of 10 and help you develop an interview-ready answer.

Good attempt, Farhan! 👍 You're thinking in the right direction. You correctly identified checking CloudWatch alarms, using `ps` and `top` to identify CPU-consuming processes, investigating recent updates, and checking application logs with `journalctl`.

Your next step is to explain **what you would do after identifying the process consuming CPU**. An interviewer wants to see how you move from monitoring to root-cause analysis, remediation, and recovery.

## 1. Mock Interview Evaluation — Question 5

**Scenario:** EC2 CPU utilization reaches 95%, and users report that the application is slow.

| Evaluation criteria | Score | Feedback |
|---|---:|---|
| CloudWatch monitoring | 9/10 | Correctly mentioned the CPU alarm and when the issue started. |
| Linux troubleshooting | 9/10 | `top` and `ps` are appropriate commands. |
| Root-cause investigation | 7/10 | Good start, but explain how you distinguish application and system-level issues. |
| Log analysis | 8/10 | `journalctl` is useful; identify the relevant service and time range. |
| Corrective action | 4/10 | You haven't explained how you would safely resolve the issue. |
| Recovery and prevention | 3/10 | Explain how you would verify recovery and prevent recurrence. |
| **Overall score** | **7/10** | Good troubleshooting fundamentals. Focus on remediation and verification. |

## 2. Improve your practical troubleshooting skills

Imagine you're connected to an Amazon Linux EC2 instance experiencing 95% CPU utilization.

### Step 1: Check CloudWatch

Review the EC2 `CPUUtilization` metric and identify when the increase began.

Check whether the CPU spike coincides with a deployment, scheduled job, traffic increase, or application update.

### Step 2: Identify the process consuming CPU

Run:

```bash
top
```

Look for processes consuming unusually high CPU.

For a sorted process list, use:

```bash
ps -eo pid,ppid,comm,%cpu,%mem --sort=-%cpu | head -15
```

This displays the processes with the highest CPU consumption.

### Step 3: Investigate the process

Suppose the output shows a Java application consuming 90% CPU.

Check its process details:

```bash
ps -fp <PID>
```

Replace `<PID>` with the actual process ID.

Then investigate the relevant application logs:

```bash
sudo journalctl -u <service-name> --since "30 minutes ago"
```

If the application writes logs to its own files, inspect those files as well.

Look for:
- Recent deployments or configuration changes.
- Excessive request volume.
- Repeated errors or retry loops.
- Resource-intensive background jobs.
- Unexpected processes or suspicious activity.

**Important:** High CPU alone doesn't prove that an application is faulty. The cause might be legitimate traffic, inefficient code, a background task, or a system process.

### Step 4: Resolve the issue safely

Choose the corrective action based on the evidence.

| Identified cause | Possible action |
|---|---|
| Application process stuck in a loop | Investigate the code or configuration and restart the service if justified. |
| Unusually high traffic | Investigate request patterns and scale capacity if necessary. |
| Resource-intensive scheduled job | Review the job and adjust its execution schedule or workload. |
| Recent faulty deployment | Roll back the deployment using the approved procedure. |
| Instance capacity insufficient | Evaluate vertical scaling or horizontal scaling. |

Avoid immediately terminating processes or rebooting the instance. Those actions can disrupt production and destroy useful diagnostic evidence.

### Step 5: Verify recovery

After applying the corrective action:

```bash
top
```

Confirm that CPU utilization has returned to an acceptable level.

Also:
- Verify that the application responds correctly.
- Check application and system logs for new errors.
- Confirm that CloudWatch CPU metrics have stabilized.
- Monitor the service to ensure the issue does not recur.

This final step is important because **resolving the immediate symptom is not the same as confirming the root cause has been fixed**.

---

## 3. Interview-ready answer

Here is a polished version you can practise.

First, I would check the CloudWatch CPUUtilization metric to identify when the CPU spike started and correlate it with any recent deployments, traffic increases, or scheduled jobs.

Next, I would connect to the instance through SSH and use the `top` and `ps` commands to identify which process is consuming the most CPU.

Once I identify the process, I would investigate it further and check the relevant application and system logs using `journalctl` or the application's log files. I would look for issues such as an application loop, a resource-intensive job, increased traffic, or a recent configuration change.

Based on the findings, I would take the appropriate corrective action, such as fixing the application issue, rolling back a faulty deployment, or scaling the infrastructure if the existing capacity is insufficient.

Finally, I would monitor CPU utilization in CloudWatch, verify that the application is responding normally, and confirm that the issue does not recur. I would also document the root cause and preventive measures.

---

# 🎯 Mock Interview — Question 6: AWS IAM Troubleshooting

Let's move to an important AWS security scenario.

**Interviewer:**

"An application running on an EC2 instance needs to upload files to an S3 bucket. The application was working yesterday, but today it is failing with the following error:"

```text
An error occurred (AccessDenied) when calling the PutObject operation:
Access Denied
```

"The EC2 instance is running, and the S3 bucket exists. How would you troubleshoot this issue and restore the application's ability to upload files securely?"

### Your turn, Farhan

Explain your troubleshooting approach. Consider:

1. How you would identify which IAM identity the application is using.
2. How you would investigate IAM permissions.
3. Whether the S3 bucket policy could be involved.
4. How you would check for explicit denies or other policy restrictions.
5. How you would resolve the issue without giving unnecessarily broad permissions.

**Answer in your own words.** I'll evaluate your response out of 10 and help you develop an interview-ready answer.