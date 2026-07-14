- [[#Session 1 (April 21)]]
- [[#Session 2 (April 26)]]
- [[#Session 3 (April 28)]]
- [[#Session 4 (May 5)]]
- [[#Session 5 (May 10)]]
- [[#Session 6 (May 12)]]
- [[#Session 7 (May 17)]]
- [[#Session 8 (May 19)]]
- [[#Session 9 (May 26)]]
- [[#Session 10 - Cybersecurity Guest Lecture (May 31)]]
- [[#Session 11 (June 2)]]
- [[#Session 12 (June 7)]]
- [[#Session 13 (June 9)]]
- [[#Session 14 (June 14)]]
- [[#Session 15 (June 16)]]
- [[#Session 16 (June 21)]]
- [[#Session 17 (June 23)]]
- [[#Session 18 (June 28)]]
- [[#Session 19 (June 30)]]
- [[#Session 20 (July 5)]]
- [[#Session 21 (July 7)]]
- [[#Session 22 (July 14)]]

# Video Recordings Folder

https://drive.google.com/drive/folders/1TZA19-jw7Cdku2dcPKSKPGKxglg5mRbV?usp=drive_link

# Session 1 (April 21)

**Slides:**
- [https://docs.google.com/presentation/d/1bU7Nv2eYI3Sv75X3FuW1tfIZXJ9z_E4W0KnniUjnQo0/edit?usp=sharing](https://docs.google.com/presentation/d/1bU7Nv2eYI3Sv75X3FuW1tfIZXJ9z_E4W0KnniUjnQo0/edit?usp=sharing)

**Practice:**
Download one of the ISO files:
- [https://www.debian.org/](https://www.debian.org/) - download
- [https://ubuntu.com/download/server](https://ubuntu.com/download/server) - download

# Session 2 (April 26)

**Slides:**
- [Iron to Cloud](https://docs.google.com/presentation/d/1TthrA9QHlS8YTxOT7m_X0cEY5hJav1UyE7YO1T0JHNc/edit?usp=sharing)
- [Blueprint to Command Line](https://docs.google.com/presentation/d/19Zg4YQN6U9gIJRT66btblR_isl9iT0boA8qcX17CEvw/)
- [The Linux Schematic](https://docs.google.com/presentation/d/1D9P6zrYQL5cZ49D_jmWOkuR_msUjH0659io6605iBjw)

**Study:**
- install a VM using ubuntu image you downloaded last time.
- get familiar with shell / CLI (command line interface) as much as you can), regardless on which linux
- practice [https://www.digitalocean.com/cdn-cgi/image/quality=75,width=1920/https://www.digitaloce[…].com%2Ftutorials%2Flinux%2Ftop-50-linux-commands.png&raw=1](https://www.digitalocean.com/cdn-cgi/image/quality=75,width=1920/https://www.digitalocean.com/api/static-content/v1/images?src=https%3A%2F%2Fdoimages.nyc3.cdn.digitaloceanspaces.com%2Ftutorials%2Flinux%2Ftop-50-linux-commands.png&raw=1) first 15-20 commands and their switches
- check the [https://www.youtube.com/watch?v=CLh2ACdXNbc](https://www.youtube.com/watch?v=CLh2ACdXNbc) video by Nana starting from 2:25 min, demonstrating some commands we are using frequently

# Session 3 (April 28)

**Slides:**
- [Linux package management, first AWS EC2](https://docs.google.com/presentation/d/1EjauPJDDzTbqwmGoK7iqGl9EIu1HEZViqEaHKCkpMSI/edit?usp=sharing)

**Study:**
- [https://www.youtube.com/watch?v=995-SYn6960](https://www.youtube.com/watch?v=995-SYn6960) - linux root dir structure and meaning
- [https://www.youtube.com/watch?v=1kicKTbK768](https://www.youtube.com/watch?v=1kicKTbK768) - starting from 2:45 min. usage of apt command and packages
- new commands to practice - top, free, htop (install if missing), df, du

# Session 4 (May 5)

**Study:**
- [https://www.youtube.com/watch?v=PNhq_4d-5ek](https://www.youtube.com/watch?v=PNhq_4d-5ek) - bash scripting
- [https://www.youtube.com/watch?v=y7DDzU0KGxw](https://www.youtube.com/watch?v=y7DDzU0KGxw) - ec2 backup/restore

# Session 5 (May 10)
  
**Slides:**
- [Storage types, LAMP](https://docs.google.com/presentation/d/1vXgW3W_f09j5pIKYQpjB_JYVPPlPiDzHL-fhtVWnDgk/edit?usp=sharing)

**Study:**
- [https://www.youtube.com/watch?v=WO5OqXVsxtw](https://www.youtube.com/watch?v=WO5OqXVsxtw) - EBS volume attach , extend demo
- [https://www.youtube.com/watch?v=6wb6Dph9AYM](https://www.youtube.com/watch?v=6wb6Dph9AYM) - web server basics
- [https://www.youtube.com/watch?v=g2fT-g9PX9o](https://www.youtube.com/watch?v=g2fT-g9PX9o) - network ports explained

**Practice 1:**
- create an ec2 instance, attach a new volume and make it available to system following official doc - [https://docs.aws.amazon.com/ebs/latest/userguide/ebs-using-volumes.html](https://docs.aws.amazon.com/ebs/latest/userguide/ebs-using-volumes.html)
- extend previously created volume by following [https://docs.aws.amazon.com/ebs/latest/userguide/recognize-expanded-volume-linux.html](https://docs.aws.amazon.com/ebs/latest/userguide/recognize-expanded-volume-linux.html)

**Practice 2:**
- install nginx web server on linux and check if it is started on port 80
- change port of web server to 8080, restart the nginx and assure 8080 port is in listen state instead of 80
- hint: use `apt` to install `ngnx`, `ss` or `netstat` commands to check ports , `vim` or `nano` to modify config files, `systemctl` to restart service

# Session 6 (May 12)

**Slides:**
- [The Internet's GPS: Understanding DNS](https://docs.google.com/presentation/d/1By_IUNFh90_Cykd3gXQOOpp_lfJwGn1nc8vnIHBY6ZE/edit?usp=sharing)
- [Nginx: The Universal Traffic Manager](https://docs.google.com/presentation/d/1w_uRkLpuANImbhdluArH0d_DdaYbAA4398_rtv9p8sQ/edit?usp=sharing)

**Study:**
- [https://www.youtube.com/watch?v=NiQTs9DbtW4](https://www.youtube.com/watch?v=NiQTs9DbtW4)
- [https://www.youtube.com/watch?v=JRZiQFVWpi8](https://www.youtube.com/watch?v=JRZiQFVWpi8) - route53 basics

**Practice in the Linux environment:**
- commands `sort`, `uniq`, `awk`, `cut`
- create a file with several lines
- print the content of that file in reverse order using command chaining - last line to first place, pre-last line to 2nd place, etc....first line from the file to last place in print

# Session 7 (May 17)

**Slides:**
- [Database Foundations](https://docs.google.com/presentation/d/1oIam6JrUte-4hNLHMRYB23vbS0kSiaO5hO67a9-nwP4/edit?usp=sharing)
- գաղտնաբառ չենք ունեցել

**Study:**
- review [https://www.youtube.com/watch?v=18rfWZYbS7o](https://www.youtube.com/watch?v=18rfWZYbS7o) WP installation on ubuntu
- install wordpress on your local VM or EC2 instance by following any instruction found on the internet, like
    - [https://ubuntu.com/tutorials/install-and-configure-wordpress](https://ubuntu.com/tutorials/install-and-configure-wordpress)
    - [https://www.digitalocean.com/community/tutorials/install-wordpress-on-ubuntu](https://www.digitalocean.com/community/tutorials/install-wordpress-on-ubuntu)
- try to automate the entire wp installation with a bash script
    - so that script should be able to
        - easy part: install web server, php components, mysql. download wordpress archive and extract it
        - difficult part: create db , db user, configure them into wordpress wp-config.php, configure web server
    - ideal case and goal, is to use that script in EC2 user data and start ready made wordpress server in AWS

# Session 8 (May 19)

**Study:**
- [https://www.youtube.com/watch?v=19WOD84JFxA](https://www.youtube.com/watch?v=19WOD84JFxA) - check on linux user management
- [https://www.youtube.com/watch?v=po8ZFG0Xc4Q](https://www.youtube.com/watch?v=po8ZFG0Xc4Q) - IP addresses
- [https://www.youtube.com/watch?v=IIicPE38O-s](https://www.youtube.com/watch?v=IIicPE38O-s) - working with ping
- all the previous homeworks are also valid (including scripting)
# Session 9 (May 26)

**Slides:**
- [IP / format](https://docs.google.com/presentation/d/1EUkaVEeOPJpok0P6yMwzqbFpKsID54kmo8iFLON2Frg/edit?usp=sharing)

**Study:**
- [https://www.youtube.com/watch?v=s_Ntt6eTn94](https://www.youtube.com/watch?v=s_Ntt6eTn94)
- [https://www.youtube.com/watch?v=e6-TaH5bkjo](https://www.youtube.com/watch?v=e6-TaH5bkjo)
- and progress with scripting (wp deployment) making it robust and pass to ec2 user-data to have wp installed with a single step

# Session 10 - Cybersecurity Guest Lecture (May 31)

Guest Lecturer: [Արամ Սիմոնյան](https://www.linkedin.com/in/aram-simonyan-work/)

**Slides:**
- [[CIAP_Security_Lesson.pptx]]



# Session 11 (June 2)

**Slides:**
- [IP / Subnetmask](https://docs.google.com/presentation/d/1KsxgH3rzZzke9kBFgjKfed8fBBOwrfKI-W6OD-2NeBc/edit?usp=sharing)
- - [MAC, ARP, Default Gateway](https://docs.google.com/presentation/d/1zr-dXtUSdUo1lFlZwgf9eUl7jCV-9o4TKNmtLhuntBg/edit?usp=sharing)
- [NAT Router](https://docs.google.com/presentation/d/1rw-raKIaW1ntc1gYD5UsgQvQcCuMTp0UXVeGxTolN8c/edit?usp=sharing)
- home crafted diagrams

![[Pasted image 20260715010210.png]]

![[Pasted image 20260715010225.png]]

![[Pasted image 20260715010238.png]]


**Study:**
- **Network**:
	- [https://www.youtube.com/watch?v=TIiQiw7fpsU](https://www.youtube.com/watch?v=TIiQiw7fpsU) - MAC address
	- [https://www.youtube.com/watch?v=cn8Zxh9bPio](https://www.youtube.com/watch?v=cn8Zxh9bPio) - ARP
	- [https://www.youtube.com/watch?v=FTUV0t6JaDA](https://www.youtube.com/watch?v=FTUV0t6JaDA) - NAT
	- [https://www.youtube.com/watch?v=pCcJFdYNamc](https://www.youtube.com/watch?v=pCcJFdYNamc) - Default Gateway
- **Linux**:
	- [https://www.youtube.com/watch?v=GGyY6fJFnW0](https://www.youtube.com/watch?v=GGyY6fJFnW0) - How To Write Bash Scripts In Linux - Complete Guide (Part 16 - Arguments)
	- [https://www.youtube.com/watch?v=HOaINcUTSg0](https://www.youtube.com/watch?v=HOaINcUTSg0) - How To Write Bash Scripts In Linux - Complete Guide (Part 15 - CRON Jobs)
	- Well structured scripting guide - [https://www.youtube.com/playlist?list=PLT98CRl2KxKGj-VKtApD8-zCqSaN2mD4w](https://www.youtube.com/playlist?list=PLT98CRl2KxKGj-VKtApD8-zCqSaN2mD4w)  

# Session 12 (June 7)

**Slides:**
- [OSI, TCP/IP, Layer 4](https://docs.google.com/presentation/d/1j4TNN-TmgQgNazc_AB_hXwHlXbid8qczC6XndsvpBgs/edit?usp=sharing)
- [Configuration management tools](https://docs.google.com/presentation/d/1kP_5dUKztHs-IkTmGEVyTvA7ThWQyv_r274REOpLgq8/edit?usp=sharing)
- [Configuration file formats](https://docs.google.com/presentation/d/1nRVvTizjVMmFG2OpKgMGDcXtlEX0RL02fcJpDAUybNo/edit?usp=sharing)
- [https://docs.ansible.com/](https://docs.ansible.com/)

**Study:**
- **Network topics**:
	- [TCP vs UDP - Explaining Facts and Debunking Myths - TCP Masterclass](https://www.youtube.com/watch?v=jE_FcgpQ7Co)
	- [UDP doesn't suck! It's the BEST L4 protocol for THESE types of applications...](https://www.youtube.com/watch?v=LaDRWycC7Iw)
	- [TCP - 12 simple ideas to explain the Transmission Control Protocol](https://www.youtube.com/watch?v=JFch3ctY6nE)
- **File formats:**
	- [Yaml Tutorial | Learn YAML in 18 mins](https://www.youtube.com/watch?v=1uFVr15xDGg)
	- [What is JSON? - for beginners!](https://www.youtube.com/watch?v=xRz2gHapBm0)
- **Ansible:**
	- [What is Ansible | Ansible Playbook explained | Ansible Tutorial for Beginners](https://www.youtube.com/watch?v=1id6ERvfozo)

**Practice:**
1. start a virtualbox VM and/or aws ec2 instance, and try to run some basic commands through the ansible. remember ansible is working via SSH
2. launch 3 aws ec2 instances, use one of those ec2 instance as a centralized configuration management host, install ansible and deploy some basic thing on other 2 instances.

# Session 13 (June 9)

**Slides:**
- [Data encapsulation / decapsulation](https://docs.google.com/presentation/d/1157nSu_PlF6zZcBDcxCfuptlLpr9ZMFLgcQSV0VOEWE/edit?usp=sharing)
- [Network routers, route tables](https://docs.google.com/presentation/d/145yPTgoPp-URao5E5GI8Sp9WpNCAmUmPDxKhsCwZles/edit?usp=sharing)
- [Network firewalls](https://docs.google.com/presentation/d/1_51hhoVrwQk9g4cb0PC5YhXRFwDjjNVzs0r3PuzmcgE/edit?usp=sharing)
- system design discussed last time - (please, note file storage section should be revisited)

![[Pasted image 20260715010611.png]]

**Study:**
- [TCP/IP Model: PDUs and Encapsulation & Decapsulation](https://www.youtube.com/watch?v=xeAe7kyejiI)
- [What is OSI Model (encapsulation/decapsulation)](https://www.youtube.com/watch?v=0y6FtKsg6J4)
- [Routing Tables | CCNA - Explained](https://www.youtube.com/watch?v=CGmTvukObOw)
- [What is a Firewall?](https://www.youtube.com/watch?v=kDEX1HXybrU)

# Session 14 (June 14)

**Slides:**
- [System Scaling Strategies](https://docs.google.com/presentation/d/1kzvLxa7jg-Cq0biM2_t2n9KXxA75s0s9vtwguutK1DM/edit?usp=sharing)
- [Load balancers](https://docs.google.com/presentation/d/1ZTcCqu_-4a0fsQQtqehND_HfLZ777aTFt88O1-jAQyo/edit?usp=sharing)
- 2nd version of system design
![[Pasted image 20260715010645.png]]

**Study:**
- [What is a LOAD BALANCER really about?](https://www.youtube.com/watch?v=LQuuoHTyYz8)
- [Vertical Vs Horizontal Scaling: Key Differences You Should Know](https://www.youtube.com/watch?v=dvRFHG2-uYs)
- [Create an Application Load Balancer (ALB) in AWS | AWS Elastic Load Balancing Tutorial for Beginners](https://www.youtube.com/watch?v=ZGGpEwThhrM)

**Practice:**
- create an application load balancer (AWS ELB) and a target group in a way that health is being checked using `/helpme` URI, instead of default `/` path

NOTE: health check should be green (healthy)

# Session 15 (June 16)

**Slides:**
- [Forward and Reverse Proxies](https://docs.google.com/presentation/d/1thWv63xospaJ9pJCV8FV3Hiu4OAxqN4pikbUa4vr2pw/edit?usp=sharing)
- [AWS VPC and subnets](https://docs.google.com/presentation/d/1OAlsp81yZ95pM7DIUfYd6iM71n0UO2TQh-dP6CA0Wtc/edit?usp=sharing)
- [AWS SG, NACL](https://docs.google.com/presentation/d/1J0gucO_0FRHXa_lO5kLZLXJD-23VeNg4CxZrT2LR5GQ/edit?usp=sharing)

**Study:**
- [Proxy vs Reverse Proxy](https://www.youtube.com/watch?v=4NB0NDtOwIQ)
- [AWS VPC & Subnets For Beginners](https://www.youtube.com/watch?v=TUTqYEZZUdc)
- [Security Groups and Network Access Control Lists (ACL)](https://www.youtube.com/watch?v=Qrg0gsehllY)
- [What is an Internet Gateway? AWS VPC Essentials](https://www.youtube.com/watch?v=u7obme-h3bc)

**Practice:**
- create a custom VPC, with public and private subnets (at least one of each)
- create an ec2 instances (A) in public sunbet with enabled public IP
- create an ec2 instance (B) in private subnet with no public IP
- connect from your laptop to instance A, and from instance A to instance B via SSH

# Session 16 (June 21)

**Study:**
- [[short] AWS Load Balancers explained but make it actually make sense](https://www.youtube.com/shorts/mbtojfukpDk) by KodeKloud
- [[short] AWS Networking Explained | VPC, Subnet, NAT, Route Tables Made Simple](https://www.youtube.com/shorts/rMjqEuDbPiQ)
- [[short] What is a Bastion Host?](https://www.youtube.com/shorts/us_zFH4Cptc)
- [Elastic IPs Tutorial](https://www.youtube.com/watch?v=UAdlVht4Xlw) - by Stephane Maarek
- [Setup a NAT Gateway on AWS](https://www.youtube.com/watch?v=Iqzgu5UEDKo)
- [AWS Networking: How NAT Gateways Work](https://www.youtube.com/watch?v=5lTBkmRyjos)
- [Jump Servers Explained | AKA Bastion Host](https://www.youtube.com/watch?v=9FN31QDLyFs) - first 2 chapters / up to 3:23 minutes

**Practice:**
- create 4 ec2 instances - 1 as bastion host, 1 as reverse proxy, 2 as web servers
- use bastion host as a deployment server running ansible
- deploy reverse proxy and web servers with a single ansible playbook

# Session 17 (June 23)

**Slides:**
- [Cloud Shared responsibility model, architectures](https://docs.google.com/presentation/d/1urGI5ZszeiXJXKdxZwH8qy4ff4NEtrtmhH3z_fo0ihI/edit?usp=sharing)
- [AWS AutoScalingGroup, Launch Template](https://docs.google.com/presentation/d/1-u-yYGDn0YBQNweDxfj13mbFivQZyswp9HVsk1XJXM0/edit?usp=sharing)
- [AWS ARN](https://docs.google.com/presentation/d/17QjQm4jvdq9_NgKoxMl86wC45iLk8sjaGOTDnNxns0s/edit?usp=sharing)

**Study:**
- [The Shared Responsibility Model For Cloud Simplified](https://www.youtube.com/watch?v=fWYC2HQKdm8)
- additional [Shared Security Responsibility Model in Cloud Explained.](https://www.youtube.com/watch?v=C62MUbAdARk)
- [AWS EC2 Auto Scaling - How it Works](https://www.youtube.com/watch?v=rcWgcFMlwFw)
- [AWS EC2 Auto Scaling : Step By Step Tutorial](https://www.youtube.com/watch?v=fwfkSxb1T-s) - pay attention to launch template part

**Practice:**
- create a new AMI based on ubuntu image and having nginx installed on top (refresh your knowledge https://www.youtube.com/watch?v=9li3TxwPCCY)
- create a new launch template using that new AMI
- create new ASG, target groups and application load balancer using that launch template
- assure health checking is successfull using http

# Session 18 (June 28)

**Slides:**
- [IAM user, group, policy](https://docs.google.com/presentation/d/1p5Pn71Bx63KvAwJHdBkaNd8vu9lxOCbJcMGwsZjpI4w/edit?usp=sharing)

**Study:**
- AWS IAM  
	- [Intro to IAM Roles and Policies on AWS](https://www.youtube.com/watch?v=BSodkwWB-8s)
	- [AWS IAM Core Concepts You NEED to Know](https://www.youtube.com/watch?v=_ZCTvmaPgao)
	- [IAM Roles on EC2 Instances Tutorial](https://www.youtube.com/watch?v=TlCuOjviOhk) (instance profile)
- **AWS CLI / SDK**
	- [AWS Access Keys, CLI and SDK Introduction](https://www.youtube.com/watch?v=tDchQ0nv7Q4)
	- [How to install and configure the AWS CLI on Windows 10](http://youtube.com/watch?v=jCHOsMPbcV0)
- AWS IAM user access keys
	- [How do I create an AWS access key?](https://www.youtube.com/watch?v=cRRaJfmLnEE)
- AWS S3 intro
	- [Amazon/AWS S3 (Simple Storage Service) Basics | S3 Tutorial, Creating a Bucket](https://www.youtube.com/watch?v=mDRoyPFJvlU)
  
**Practice:**
1. create a new IAM user with permissions creating only NAT GW
2. there is no need to give aws console access to that user, hence that user will manage aws via CLI
3. install AWS CLI locally and create a NAT GW using access keys of newly create user (1)
4. share IAM policy created by your and AWS CLI used by you under this post in the thread

# Session 19 (June 30)

**Slides:**
- [AWS CLI, API, SDK](https://docs.google.com/presentation/d/1ad5y2iHapcglI9SfpoCu9aCBkl7Mg5ro09VG2IaW5sQ/edit?usp=sharing)
- [AWS S3 intro](https://docs.google.com/presentation/d/1HhwqRvrzJcYNfx_7wbOnEnRLe78d2_2EvDIqPa3E8XQ/edit?usp=sharing)

Attaching also bash script based on aws cli creating entire aws resources we have learnt so far - network layer, ec2 stack:
```bash
#!/bin/bash

# Exit immediately if a command exits with a non-zero status
set -e

# ==========================================
# CONFIGURATION VARIABLES
# ==========================================
REGION="eu-north-1"
PREFIX="stockholm-demo"
VPC_CIDR="192.168.0.0/24"
SUBNET_A_CIDR="192.168.0.0/25"
SUBNET_B_CIDR="192.168.0.128/25"
INSTANCE_TYPE="t3.micro"
# Official Ubuntu 24.04 LTS AMI for eu-north-1
AMI_ID="ami-0aba19e56f3eaec05"

echo "🚀 Starting Idempotent AWS Infrastructure Deployment in $REGION..."

# ==========================================
# PHASE 1: NETWORKING (VPC, SUBNETS, IGW)
# ==========================================

# 1. Create VPC
VPC_ID=$(aws ec2 describe-vpcs --region "$REGION" --filters "Name=tag:Name,Values=${PREFIX}-vpc" --query "Vpcs[0].VpcId" --output text)
if [ "$VPC_ID" == "None" ] || [ -z "$VPC_ID" ]; then
    echo "Creating VPC..."
    VPC_ID=$(aws ec2 create-vpc --cidr-block "$VPC_CIDR" --region "$REGION" --query "Vpc.VpcId" --output text)
    aws ec2 create-tags --resources "$VPC_ID" --tags "Key=Name,Value=${PREFIX}-vpc" --region "$REGION"
    # Enable DNS hostnames so Nginx handles routing correctly
    aws ec2 modify-vpc-attribute --vpc-id "$VPC_ID" --enable-dns-hostnames "{\"Value\":true}" --region "$REGION"
else
    echo "✅ VPC already exists: $VPC_ID"
fi

# 2. Create Internet Gateway
IGW_ID=$(aws ec2 describe-internet-gateways --region "$REGION" --filters "Name=attachment.vpc-id,Values=$VPC_ID" --query "InternetGateways[0].InternetGatewayId" --output text)
if [ "$IGW_ID" == "None" ] || [ -z "$IGW_ID" ]; then
    echo "Creating and Attaching Internet Gateway..."
    IGW_ID=$(aws ec2 create-internet-gateway --region "$REGION" --query "InternetGateway.InternetGatewayId" --output text)
    aws ec2 attach-internet-gateway --vpc-id "$VPC_ID" --internet-gateway-id "$IGW_ID" --region "$REGION"
    aws ec2 create-tags --resources "$IGW_ID" --tags "Key=Name,Value=${PREFIX}-igw" --region "$REGION"
else
    echo "✅ Internet Gateway already attached: $IGW_ID"
fi

# 3. Create Subnet A
SUBNET_A_ID=$(aws ec2 describe-subnets --region "$REGION" --filters "Name=tag:Name,Values=${PREFIX}-subnet-a" --query "Subnets[0].SubnetId" --output text)
if [ "$SUBNET_A_ID" == "None" ] || [ -z "$SUBNET_A_ID" ]; then
    echo "Creating Subnet A..."
    SUBNET_A_ID=$(aws ec2 create-subnet --vpc-id "$VPC_ID" --cidr-block "$SUBNET_A_CIDR" --availability-zone "${REGION}a" --region "$REGION" --query "Subnet.SubnetId" --output text)
    aws ec2 create-tags --resources "$SUBNET_A_ID" --tags "Key=Name,Value=${PREFIX}-subnet-a" --region "$REGION"
else
    echo "✅ Subnet A already exists: $SUBNET_A_ID"
fi

# 4. Create Subnet B
SUBNET_B_ID=$(aws ec2 describe-subnets --region "$REGION" --filters "Name=tag:Name,Values=${PREFIX}-subnet-b" --query "Subnets[0].SubnetId" --output text)
if [ "$SUBNET_B_ID" == "None" ] || [ -z "$SUBNET_B_ID" ]; then
    echo "Creating Subnet B..."
    SUBNET_B_ID=$(aws ec2 create-subnet --vpc-id "$VPC_ID" --cidr-block "$SUBNET_B_CIDR" --availability-zone "${REGION}b" --region "$REGION" --query "Subnet.SubnetId" --output text)
    aws ec2 create-tags --resources "$SUBNET_B_ID" --tags "Key=Name,Value=${PREFIX}-subnet-b" --region "$REGION"
else
    echo "✅ Subnet B already exists: $SUBNET_B_ID"
fi

# 5. Route Table Configuration
ROUTE_TABLE_ID=$(aws ec2 describe-route-tables --region "$REGION" --filters "Name=vpc-id,Values=$VPC_ID" "Name=route.gateway-id,Values=$IGW_ID" --query "RouteTables[0].RouteTableId" --output text)
if [ "$ROUTE_TABLE_ID" == "None" ] || [ -z "$ROUTE_TABLE_ID" ]; then
    echo "Configuring Routing to Internet..."
    ROUTE_TABLE_ID=$(aws ec2 describe-route-tables --region "$REGION" --filters "Name=vpc-id,Values=$VPC_ID" --query "RouteTables[0].RouteTableId" --output text)
    aws ec2 create-route --route-table-id "$ROUTE_TABLE_ID" --destination-cidr-block "0.0.0.0/0" --gateway-id "$IGW_ID" --region "$REGION"
    aws ec2 associate-route-table --subnet-id "$SUBNET_A_ID" --route-table-id "$ROUTE_TABLE_ID" --region "$REGION" > /dev/null
    aws ec2 associate-route-table --subnet-id "$SUBNET_B_ID" --route-table-id "$ROUTE_TABLE_ID" --region "$REGION" > /dev/null
else
    echo "✅ Routing Rules already configured on table: $ROUTE_TABLE_ID"
fi


# ==========================================
# PHASE 2: SECURITY GROUPS & COMPUTATION
# ==========================================

# 1. ALB Security Group
ALB_SG_ID=$(aws ec2 describe-security-groups --region "$REGION" --filters "Name=group-name,Values=${PREFIX}-alb-sg" --query "SecurityGroups[0].GroupId" --output text)
if [ "$ALB_SG_ID" == "None" ] || [ -z "$ALB_SG_ID" ]; then
    echo "Creating ALB Security Group..."
    ALB_SG_ID=$(aws ec2 create-security-group --group-name "${PREFIX}-alb-sg" --description "Allow public HTTP traffic" --vpc-id "$VPC_ID" --region "$REGION" --query "GroupId" --output text)
    aws ec2 authorize-security-group-ingress --group-id "$ALB_SG_ID" --protocol tcp --port 80 --cidr 0.0.0.0/0 --region "$REGION"
else
    echo "✅ ALB Security Group already exists: $ALB_SG_ID"
fi

# 2. EC2 Security Group
EC2_SG_ID=$(aws ec2 describe-security-groups --region "$REGION" --filters "Name=group-name,Values=${PREFIX}-ec2-sg" --query "SecurityGroups[0].GroupId" --output text)
if [ "$EC2_SG_ID" == "None" ] || [ -z "$EC2_SG_ID" ]; then
    echo "Creating EC2 Security Group..."
    EC2_SG_ID=$(aws ec2 create-security-group --group-name "${PREFIX}-ec2-sg" --description "Allow HTTP only from ALB" --vpc-id "$VPC_ID" --region "$REGION" --query "GroupId" --output text)
    aws ec2 authorize-security-group-ingress --group-id "$EC2_SG_ID" --protocol tcp --port 80 --source-group "$ALB_SG_ID" --region "$REGION"
else
    echo "✅ EC2 Security Group already exists: $EC2_SG_ID"
fi

# 3. Target Group
TG_ARN=$(aws elbv2 describe-target-groups --region "$REGION" --names "${PREFIX}-tg" --query "TargetGroups[0].TargetGroupArn" --output text 2>/dev/null || echo "None")
if [ "$TG_ARN" == "None" ]; then
    echo "Creating Target Group..."
    TG_ARN=$(aws elbv2 create-target-group --name "${PREFIX}-tg" --protocol HTTP --port 80 --vpc-id "$VPC_ID" --region "$REGION" --query "TargetGroups[0].TargetGroupArn" --output text)
else
    echo "✅ Target Group already exists: $TG_ARN"
fi

# 4. Application Load Balancer (ALB)
ALB_ARN=$(aws elbv2 describe-load-balancers --region "$REGION" --names "${PREFIX}-alb" --query "LoadBalancers[0].LoadBalancerArn" --output text 2>/dev/null || echo "None")
if [ "$ALB_ARN" == "None" ]; then
    echo "Creating Application Load Balancer..."
    ALB_ARN=$(aws elbv2 create-load-balancer --name "${PREFIX}-alb" --subnets "$SUBNET_A_ID" "$SUBNET_B_ID" --security-groups "$ALB_SG_ID" --region "$REGION" --query "LoadBalancers[0].LoadBalancerArn" --output text)
    
    # Create Listener to tie ALB to Target Group
    aws elbv2 create-listener --load-balancer-arn "$ALB_ARN" --protocol HTTP --port 80 --default-actions Type=forward,TargetGroupArn="$TG_ARN" --region "$REGION" > /dev/null
else
    echo "✅ ALB already exists: $ALB_ARN"
fi

# 5. Launch Template
LT_EXISTS=$(aws ec2 describe-launch-templates --region "$REGION" --launch-template-names "${PREFIX}-template" --query "LaunchTemplates[0].LaunchTemplateId" --output text 2>/dev/null || echo "None")
if [ "$LT_EXISTS" == "None" ]; then
    echo "Creating Launch Template..."
    
    # Inline User Data script Base64 encoded natively by bash
    USER_DATA_BASE64=$(echo -n '#!/bin/bash
sudo apt-get update -y
sudo apt-get install -y nginx
sudo systemctl start nginx
echo "<h1>Hello from Stockholm ASG via AWS CLI</h1>" | sudo tee /var/www/html/index.html' | base64 | tr -d '\n')

    # Construct JSON parameters for network configuration
    LAUNCH_DATA="{\"ImageId\":\"$AMI_ID\",\"InstanceType\":\"$INSTANCE_TYPE\",\"UserData\":\"$USER_DATA_BASE64\",\"NetworkInterfaces\":[{\"DeviceIndex\":0,\"AssociatePublicIpAddress\":true,\"Groups\":[\"$EC2_SG_ID\"]}]}"
    
    aws ec2 create-launch-template --launch-template-name "${PREFIX}-template" --launch-template-data "$LAUNCH_DATA" --region "$REGION" > /dev/null
else
    echo "✅ Launch Template already exists."
fi

# 6. Auto Scaling Group (ASG)
ASG_EXISTS=$(aws autoscaling describe-auto-scaling-groups --region "$REGION" --auto-scaling-group-names "${PREFIX}-asg" --query "AutoScalingGroups[0].AutoScalingGroupARN" --output text 2>/dev/null || echo "None")
if [ "$ASG_EXISTS" == "None" ] || [ -z "$ASG_EXISTS" ]; then
    echo "Creating Auto Scaling Group..."
    aws autoscaling create-auto-scaling-group \
        --auto-scaling-group-name "${PREFIX}-asg" \
        --launch-template "LaunchTemplateName=${PREFIX}-template,Version=\$Latest" \
        --vpc-zone-identifier "${SUBNET_A_ID},${SUBNET_B_ID}" \
        --min-size 1 \
        --max-size 3 \
        --desired-capacity 2 \
        --target-group-arns "$TG_ARN" \
        --region "$REGION"
else
    echo "✅ Auto Scaling Group already exists."
fi

# ==========================================
# PHASE 3: OUTPUT RESULT
# ==========================================
ALB_DNS=$(aws elbv2 describe-load-balancers --region "$REGION" --names "${PREFIX}-alb" --query "LoadBalancers[0].DNSName" --output text)
echo "--------------------------------------------------------"
echo "🎉 Deployment Sync Complete!"
echo "🔗 Access your load-balanced app here: http://$ALB_DNS"
echo "--------------------------------------------------------"
```
# Session 20 (July 5)

**Slides:**
- [AWS polices - identity-based, resource-based](https://docs.google.com/presentation/d/1a7UY0E5t1fgGd1QWqyxjc8I0hXZD5PrpnCWmB4CKh2c/edit?usp=sharing)
- [AWS storages - EBS, EFS, S3](https://docs.google.com/presentation/d/1VVAFT9qgm6WQySBgRMPEh244FGQ3GqeMEl23NwWDsJ8/edit?usp=sharing)
- [AWS EFS](https://docs.google.com/presentation/d/1ICs8LOuOjGk4gDUYAnDiM1crzmA2XCDsbinyRWH1QcI/edit?usp=sharing)
- AWS S3 related slide deck has been shared with previous materials and discussed yesterday.

**Study:**
- [AWS S3 Tutorial For Beginners](https://www.youtube.com/watch?v=tfU0JEZjcsg)
- [Amazon S3 Storage Classes & Lifecycle Policies](https://www.youtube.com/watch?v=LP_KT6U73M0)
- [AWS IAM Core Concepts You NEED to Know](https://www.youtube.com/watch?v=_ZCTvmaPgao) (refresh)
- [AWS S3 Bucket Policy vs IAM - What's the Difference?](https://www.youtube.com/watch?v=gWAwqY76JQs)
- [Amazon EFS file system creation, mounting & settings](https://www.youtube.com/watch?v=Aux37Nwe5nc)

**Extra:**
- - [AWS re:Invent 2024 - Simple Elastic File Systems: A Deep Dive into Amazon EFS (STG344)](https://www.youtube.com/watch?v=m03ICK5ZsA0) (±30min)
- [AWS re:Invent 2024 - Dive deep on Amazon S3 (STG302)](https://www.youtube.com/watch?v=NXehLy7IiPM) (±1hr)
- [Migrating your Amazon EBS volumes from GP2 to GP3](https://www.youtube.com/watch?v=ajhDlm5Yvpc) (5min)

**Practice:**
1. create a file system on EFS, an S3 bucket, 2 EC2 instances
2. be sure both EC2 instances can mount the same EFS drive and write files into it
3. be sure S3 bucket allows read access from both EC2 instances, and write access only from one of that 2 EC2 instances.

# Session 21 (July 7)

**Study:**
- [Amazon RDS vs. EC2: The Ultimate AWS Database Comparison](https://www.youtube.com/watch?v=6LksnFe6rp4)
- [AWS RDS Tutorial: Setting up a Database in Amazon RDS | KodeKloud](https://www.youtube.com/watch?v=ylmwaDUMV9c)

**Practice:**
- setup wordpress on ec2 instance and setup its database on RDS
- ec2 instance should be in public subnet and can be with public IP, RDS instance - in private subnet
- wordpress should be well up and running

# Session 22 (July 14)

**Slides:**
- [AWS RDS and Aurora](https://docs.google.com/presentation/d/1CBLkMsxCDEF_o9DV1F42b4kiGB1sSijMGTF6xCRyvpQ/edit?usp=sharing)
- [AWS Aurora Serverless](https://docs.google.com/presentation/d/1LelFA-LHfjaKYMdhk5jkqt1pNc-Pt_ZvHQihOCFOiW8/edit?usp=sharing)
- [DB replication with MySQL](https://docs.google.com/presentation/d/1LQNU7pOr_vv1JcmJqOLvS4WsfBrldikUorsP8tJ4bwI/edit?usp=sharing)
- [AWS EC2 pricing models](https://docs.google.com/presentation/d/13rCc2eoy3fUhEIpu9YTBv0yMQvOAhpcgSHy41-8EH3E/edit?usp=sharing)

**Study:**
- **Databases:**
	- [Amazon Aurora vs. Amazon RDS (MySQL/PostgreSQL)](https://www.youtube.com/watch?v=YGeku8zP7hA)
	- extra [AWS re:Invent 2024 - Deep dive into Amazon Aurora and its innovations (DAT405)](https://www.youtube.com/watch?v=kVVdHezNTpw) ~1hr
- **Money:**
	- [Amazon/AWS EC2 Pricing Simply Explained | On-Demand, Spot, Reserved, Savings Plans](https://www.youtube.com/watch?v=-t148tYgnJU)
- **Cloud-native architecture in different interpretations:**
	- [Cloud-Native Architecture Explained: 5 Key Principles | Cloud-Native Concepts | Architecture Design](https://www.youtube.com/watch?v=pgzUqkC6QZM) - i like this option more
	- [But What Is Cloud Native Really All About?](https://www.youtube.com/watch?v=p-88GN1WVs8)
- **Extra - opinions on cloud first strategy:**
	- [How “Cloud-First” Turned Into a Money Pit](https://www.youtube.com/watch?v=DHe9AlwoyYo)
	- [Cloud First Strategy - Why It's Often A Recipe For Disaster](https://www.youtube.com/watch?v=WsOpDVxfcW8)

**Practice:**

Goal is having application deployed on mixed instance types:
- create a launch template with Amazon Linux AMI and the following user data
```bash
#!/bin/bash
dnf update -y
dnf install httpd -y
systemctl start httpd
systemctl enable httpd
echo "<h1>Hello from $(hostname -f)</h1>" > /var/www/html/index.html
```
- create a load balancer and target group using that launch template
- create an ASG and attach to load balancer taking into account the following recommendation
```
Scroll down to Instance purchase options and select Combine purchase models and instance types.

Set the Instance distribution:

- On-Demand base: 2 (This ensures that the first 2 instances launched are always reliable On-Demand instances).
- On-Demand percentage above base: 30% (Any instance launched beyond the baseline 2 will follow a 70% Spot / 30% On-Demand split).

Set Instance type requirements:

- Add multiple flexible alternatives to mitigate Spot termination risks (e.g., t3.micro, t3a.micro, t2.micro).

Spot allocation strategy: Set to Price-capacity-optimized (AWS will automatically pull from the Spot pools that are least likely to be interrupted and cost the least).

Under Configure group size and scaling policies:

- Desired capacity: 4 (This will yield 2 base On-Demand instances, and 2 Spot instances).
- Min capacity: 2
- Max capacity: 10
```
- verify service accessibility via LB, web interface should show the hostname, and based on that hostname you can check if different instance types are being utilized

# Homework - Session 23 (July xxx)
# Homework - Session 24 (July xxx)
# Homework - Session 25
# Homework - Session 26
# Homework - Session 27
# Homework - Session 28
# Homework - Session 29
# Homework - Session 30





# Literature

- [The Phoenix Project By Gene Kim, Kevin Behr, George Spafford](https://itrevolution.com/product/the-phoenix-project/) - վեպի տեսքով նկարագրվում ա ՏՏ կազմակերպության խնդիրները ու մարդկանց ներգրավվածությունը: ինքս չեմ կարդացել, քանզի ֆորմատը յուրահատուկ ա, սկսեցի ու չկարողացա շարունակել: երեւի նրանից էր որ արդեն մի 93 տարի ՏՏ ոլորտում աշխատում էի, իսկ ինքը նախատեսված ա սկսնակների համար:
- [The DevOps Handbook, Second Edition](https://itrevolution.com/product/the-devops-handbook-second-edition/) - ավելի տեխնիկական, ու մտածելակերպի ու որակի մասին հրաշալի գիրք:

# Other Materials

Մի հրաշալի բացատրություն kodekloudի կողմից ժամանակակից դիփլոյմենթի տեսակներից մեկի՝ blue-green deploymentի մասին հենց մեր վերջերս անցած սերվիսների հիման վրա -  
[https://youtu.be/X-NfwLUBco4?si=qEVuRhF534tXUq5v](https://youtu.be/X-NfwLUBco4?si=qEVuRhF534tXUq5v)


