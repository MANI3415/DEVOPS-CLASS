- **DEVOPS--CLASSLINK:-1 (18-01-2022 to 13-02-2022)**
  - [Zoom Link](https://zoom.us/j/96078845638?pwd=dEZzSTBhQUtJNnR3VndtUDVYL1M1Zz09)
  - Zoom Credentials: Zoom id: 960 7884 5638
  - Passcode: devops
- **DEVOPS--CLASSLINK:-2 (14-02-2022 to till now)**
  - [Zoom Link](https://us02web.zoom.us/j/82959733869?pwd=Snl1WHNmWDZML1lvSjM4UCtkMFZ2QT09)
  - Zoom Credentials: Zoom id: 829 5973 3869
  - Passcode: zVbm7t
----------------------------------------------------------------------------------------------------------------------------------------------
**DAY-1 (18-01-2022)**
- [DAY-1_VIDEO LINK](https://www.youtube.com/watch?v=d3u72SxI7ZE&t=445s)
- **TOPICS DISCUSSED ON 18/01/2022**
  - DEVOPS INTRODUCTION

----------------------------------------------------------------------------------------------------------------------------------------------
**DAY-2 (19-01-2022)**
- [DAY-2_VIDEO LINK](https:https://www.youtube.com/watch?v=n4tlrIbEbPs)
- **TOPICS DISCUSSED ON 19/01/2022**
  - LINUX COMMANDS DISCUSSED

----------------------------------------------------------------------------------------------------------------------------------------------
**DAY-3 (20-01-2022)
- [DAY-3_VIDEO LINK](https:https://www.youtube.com/watch?v=xN1I4MTWbZo)
- **TOPICS DISCUSSED ON 20/01/2022**
  - LINUX COMMANDS DISCUSSED

-----------------------------------------------------------------------------------------------------
**DAY-4 (21-01-2022)**
-[DAY-4_VIDEO LINK](https:https://www.youtube.com/watch?v=vN3JCmrT9GA)
- **TOPICS DISCUSSED ON 21/01/2022**
  - DEVOPS TOOLS
    - AWS
    - GITHUB
    - DOCKER
    - MAVEN
    - JENKINS
    - ANSIBLE
    - KUBERNETES
    - SPLUNK
  - AWS ACCOUNT CREATION
  - DEMO OF EC2(SERVER LAUNCH)

-----------------------------------------------------------------------------------------------------
**DAY-5 (24-01-2022)**
- [DAY-5_VIDEO LINK](https://www.youtube.com/watch?v=zho0BsWVU6M)
- **TOPICS DISCUSSED ON 24/01/2022:**
  - EC2(SERVER LAUNCH)
  - SECURITY GROUPS

------------------------------------------------------------------------------------------------------
**DAY-6 (25-01-2022)**
- [DAY-6_VIDEO LINK](https://www.youtube.com/watch?v=qRrpPEus0go&t=2933s)
- **TOPICS DISCUSSED ON 25/0/2022:**
  - IAM(IDENTITY ACCESS MANAGEMENT)
  - MFA(MULTI FACTOR AUTHANTICATION)
    - DASHBOARD
    - USER--CREATE USER
    - ROLES--CREATE RULES(HOW MANY SERVICES ARE YOU NEED)
    - POLICES--CREATE POLICES(SERVER ACCESSABILITY TIME EXAMPLE:SOMETIMES SERVER ACCESSABILITY INCREASED AND SOMETIME LOW)
    - IDENTITY PRIVIDER

-----------------------------------------------------------------------------------------------------
**DAY-7 (27-01-2022)**
- [DAY-7_VIDEO LINK](https://www.youtube.com/watch?v=ZuI3sB7FUho)
- **TOPICS DISCUSSED ON 27/01/2022**
  - S3BUCKET(SIMPLE STORAGE SERVICE)
  - IT IS STORE THE FILES RANGE(0-5GB)
  - UPLOADING FILE IN S3BUCKET AND ACCESS 

------------------------------------------------------------------------------------------------------
**DAY-8 (28/0/2022)**
- [DAY-8_VIDEO LINK](https://youtu.be/klHKLSLHObI)
- **TOPICS DISCUSSED ON 28/01/2022**
  - S3 BUCKET
  - LOAD BALANCING
  - CREATING VPC(VIRTUAL PRIVATE CLOUD):
    - IP ADDRESSES
    - SUBNETS
    - ROUTING
    - INTERNET GATEWAY

------------------------------------------------------------------------------------------------------
**DAY-9 (29-01-2022)**
- [DAY-9_VIDEO LINK](https://youtu.be/vuSYOf9-_dM)
- **Topics discussed on 29/1/2022:**
  - VPC Creation
  - Subnet Creation
  - Routing Table Creation
  - Attaching the same to internet gateway
  - discussed about Public DNA
  - discussed about Public VPC
  - Deleting the created VPC

**step by step launch ec2 by using created vpc**
  
- **step-1**
- **openvpc**
- yourvpcs
------------
create vpc--vpcname--ipv4-10.0.0.0/16-create vpc--actions-editdnshostname--enable--save changes

- **step-2**
- **subnets**
--------------
create subnet--given already created vpc id--subnet name--any one select availability zone--ipv4-10.0.0.0/16--create subnet

- **step-3**
- **internet gateway**
---------------------
create internet gateway--name--create internet gateway--actions--attach to vpc--given already created vpc id--give ok

- **step-4**
- **route table**
-----------------
alredy one route table alredy created--select the name--routes--edit routes--add route--0.0.0.0/0--select internet gateway--select the alredy created gate way--save changes
select sunnet associate--select edit subnet associate--select given one--ok

- **step-5**
- **open ec2**
------------
launche instance--select any one of ami--select t2 micro free trair--choose instance type---select the alredy create vpc-to launch the ec2--open git bash to connection--now ec2 is launched by using created vpc
without any error.

------------------------------------------------------------------------------------------------------------------------------
**DAY-10 (31-01-2022)**
- [DAY-10_VIDEO LINK](https://youtu.be/EFZzknfFXsg)
- **Topics discussed on 31/1/2022:**
  - VPC creation

-------------------------------------------------------------------------------------------------------------------------------
**DAY-11 (01-02-2022)**
- [DAY-11_VIDEO LINK](https://youtu.be/HaQvaEP2SJ8)
- **TOPICS DISCUSSED ON 01/02/2022:**
- NATGATE WAY

- Load Balancing--
- Auto Scaling--High Availability

- Elastic Load Balancer(ELB)
  - microservices                             
    - /user                       
    - /app                       
    - /user-name
  - target group 
    - customized apps
    - (nginx)(apache)
  - round robin mechanism
    - Request--Response
   
- EFS(Elastic File System)

- **Network Load Balancer is a Faster Then Application Load Balancer**

- **NETWORK LOAD BALANCER**
   - NLB IS WORKS ON TCP/UDP PROTOCOL
   - OSI LAYER
   - PORT BASED ROUTING

- **APPLICATION LOAD BALANCER:**
   - ALB------HTTP/HTTPS
   - APPLICATION LAYER
   - PATH BASED ROUTING

---------------------------------------------------------------------------------------------------------------------------------
**DAY-12 (02-02-2022)**
- [DAY-12_VIDEO LINK](https://www.youtube.com/watch?v=eA0N_elaO7I)
- **TOPICS DISCUSSED ON 02/02/2022**

- first we launch the EC2 Instances
- load balancing
    - Load Balancers             
    - Target Groups

- **STEP-1:-**
  - **FIRST WE CREATING TARGET GROUPS:-**

   1. CREATE TARGET GROUPS FOLLOW THE APPICATION LOAD BALANCER PROTOCOL(HTTP/HTTPS)
   2. SELECT TARGET GROUPS-CREATE TARGET GROUPS--GIVE THE TARGET NAME AND SELECT APPLICATION LOAD BALANCER PROTOCOL--AND SELECT TO REGISTER TARGETS INSTANCES--INCLUDE AS PENDING       BELOW--CREATE TARGET GROUP
 
   1. CREATE TARGET GROUPS FOLLOW THE NETWORK LOAD BALANCER PROTOCOL(TCP/UDP/TLS)
   2. SELECT TARGET GROUPS-CREATE TARGET GROUPS--GIVE THE TARGET NAME AND SELECT NETWORK LOAD BALANCER PROTOCOL--AND SELECT TO REGISTER TARGETS INSTANCES--INCLUDE AS PENDING           BELOW--CREATE TARGET GROUP

- **STEP-2:-**
  - **LOAD BALANCERS:-**
  - ALB CREATION:-
    - SELECT CREATE LOAD BALANCER--SELECT APPLICATION LOAD BALANCER--GIVE THE LOAD BALANCER NAME AND SELECT THE ALP TARGET GROUP--CREATE LOAD BALANCER
  - NLB CREATION:-
    - SELECT CREATE LOAD BALANCER--SELECT NETWORK LOAD BALANCER--GIVE THE LOAD BALANCER NAME AND SELECT THE NLB TARGET GROUP--CREATE LOAD BALANCER

- Auto Scaling
    - Launch Configurations
    - Auto Scaling Groups

- **STEP-3:-**
  - **Launch Configurations:-**
  
   1. Select the Launch Configurations create Launch Configurations--first we create the launch templates--and give the template name and select AMI(amazon machine image)--and         select any one of security group--create launch template
   2. now create Launch Configurations--give name,select any one of AMI and select instance(t2-micro),and select key pair is requried or not--create Launch Configurations

- **STEP-4:-**
  - **Auto Scaling Groups:-**
  - Select Auto Scaling Groups--Create Auto Scaling Groups--
  - Step 1:
    - Choose launch template or configuration:-
      -- and give name And Select Switch to Launch configuration And Select A Launch configuration --Next
  - Step 2:
    - Choose instance launch options:-
      -- Select Availabiliy Zones--Next
  - Step 3 (optional)
    - Configure advanced options:-
      -- Select Attach to an existing load balancer--Select Existing load balancer target groups--Select Health check type(ELB)--Next
  - Step 4 (optional)
    - Configure group size and scaling policies:-
      -- Next
  - Step 5 (optional)
    - Add notifications:-
      -- Next
  - Step 6 (optional)
    - Add tags:-
      -- Next
  - Step 7
    - Review:-
      -- Create Auto Scaling Groups
   
 -------------------------------------------------------------------------------------------------------------
 **DAY-13 (03-02-2022)**
- [DAY-13_VIDEO LINK](https://www.youtube.com/watch?v=FjZyVZJvEg0)
- **TOPICS DISCUSSED ON 03/02/2022**
  - Config Group Size & Scaling Polices
  - **Config Group Size**
    - Group Size Optimal
    - Check The Activity--Check The Instances
  - **Scaling polices*
    - none
    - key and value optional
 
- create a dynamic scaling policy
- create a cloud watch
  - select matric--alarm
  
   - static                              
   - greater>=threshold             
   - value-70                                      

   - select ec2 
   - auto scaling group

   -  matric name
   -   cpu  utilization
   -   Auto scaling group

- simple notification service()

------------------------------------------------------------------------------------------------------
 **DAY-14 (04-02-2022)**
- [DAY-14_VIDEO LINK](https://www.youtube.com/watch?v=FjZyVZJvEg0&t=20s)
- **TOPICS DISCUSSED ON 04/02/2022**
   - **cloudwatch**

-----------------------------------------------------------------------------
**DAY-15 (05-02-2022)**
- [DAY-15_VIDEO LINK](https:https://www.youtube.com/watch?v=GnhaFyLmJMQ)
- **TOPICS DISCUSSED ON 05/02/2022**
  - ec2 server launch using redhat
  - ec2 server launch using ubantu

------------------------------------------------------------------------
**DAY-16 (07-02-2022)**
- [DAY-16_VIDEO LINK](https://youtu.be/GxSXp6Qw7XE)
- **TOPICS DISCUSSED ON 07/02/2022**
  - Terraform-Hashicorp
  - steps in Terrafoem
    - configuration file
    - init--plan--apply
  - IAC tools
  - Docker Ansible,puppet,saltstack,cloudformation

-----------------------------------------------------------------------
**DAY-17 (08-02-2022)**
- [DAY-17_VIDEO LINK](https://www.youtube.com/watch?v=7AHa_VBeGqk&t=2202s)
- **TOPICS DISCUSSED ON 08/02/2022**
- EC2 SERVER LAUNCH USING TERRAFORM
1. first we launch the ubantu server 20.04
2. connect to git bash using ssh key
   - convert to root user: sudo -i
   - update:sudo apt-get update
3. install terraform in ubantu 20.04:-
- Repository Configuration:
 1. curl -fsSL https://apt.releases.hashicorp.com/gpg | sudo apt-key add -
 2. sudo apt-add-repository "deb [arch=$(dpkg --print-architecture)] https://apt.releases.hashicorp.com $(lsb_release -cs) main"
 3. sudo apt install terraform
- Choosing Terraform Versions:
  1. apt policy terraform
  2. sudo apt install terraform=0.14.0
- check the version:
  - terraform --version
4. terraform to be configured for aws account
   - choose iam accpunt and select the manage access keys--
   - create new access key
- connect to access keys and seceret keys
1. file1 - first we create a file using .tf extension
  - vi provider.tf
  - goto google search aws provider and copy the
  - --------------
  - Usage:
   - provider "aws" {
   - region     = "us-west-2"
   - access_key = "my-access-key"
   - secret_key = "my-secret-key"
   - }
-------------------
2. file2 - and create another file
   - vi main.tf --and search google main.tf 
-------------------
   - resource "aws_instance" "app_server" {
   - ami = ""
   - instance_type = "t2.micro" 
   - tags = {
   - Name = "ExampleAppServerInstance"
   - }
   - }  
--------------------
5. innatiated the terraform
   - terraform init
6. validate the terraform
   - terraform validate
7. terraform apply
   - terraform apply  
 - now server is launch
8. terminate the server
   - terraform destroy


- Using infrastructure as a code
------------------------------
- **overview of launch server using terraform concept:-**
  1. terraform install in server
  2. terraform to be configured for aws account
  3. terraform-- provide.tf--region,aws access key,secret key addes
  4. terraform--vi main.tf--ec2--name,ami,t2.nicro,tag
  5. terraform init
  6. terraform validation
  7. terraform apply
----------------------------------
- **launching the multiple instances using terraform**
1. Goto Google search launch multiple instances for aws terraform
2. Goto vi main.tf
3. -----------------------
   - resource "aws_instance" "app_server" {
   - ami = ""
   - instance_type = "t2.micro"
   - count=3
   - tags = {
   - Name = "ExampleAppServerInstance"
   - }
   - }  
   -------------------------------
3. terraform init
4. terraform validate
5. terraform apply
6. adding security groups
  - goto google search main.tf terraform security group

- :wq!  ----save&quit

---------------------------------------------------------------------------------------------------------
**DAY-18 (09-02-2022)**
- [DAY-18_VIDEO LINK](https://www.youtube.com/watch?v=XFXYphx8h0k&t=570s)
- **TOPICS DISCUSSED ON 09/02/2022**
  - VARIABLES CREATION USING TERRAFORM

---------------------------------------------------------------------------------------------------------------
**DAY-19 (10-02-2021)**
- [DAY-19_VIDEO LINK](https://www.youtube.com/watch?v=XFXYphx8h0k&t=476s)
- **TOPICS DISCUSSED ON 10/02/2022**
----------------
- Topic variables
1. first we launch the ubantu server 20.04
2. connect to git bash using ssh key
   - convert to root user: sudo -i
   - update:sudo apt-get update
3. install terraform in ubantu 20.04:-
- Repository Configuration:
  - curl -fsSL https://apt.releases.hashicorp.com/gpg | sudo apt-key add -
  - sudo apt-add-repository "deb [arch=$(dpkg --print-architecture)] https://apt.releases.hashicorp.com $(lsb_release -cs) main"
  - sudo apt install terraform
- Choosing Terraform Versions:
  - apt policy terraform
  - sudo apt install terraform=0.14.0
- check the version:
  - terraform --version
4. terraform to be configured for aws account
   - choose iam accpunt and select the manage access keys--
   - create new access key
- connect to access keys and seceret keys
1. file1 - first we create a file using .tf extension
  - vi provider.tf
  - goto google search provider.tf and copy the
------------------
- **provider.tf**
-----------------
- provider "aws" {
  - region     = "ap-south-1"
  - access_key = "AKIAUJ5V5GF7WEYIBSXD"
  - secret_key = "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"
- }

2. file2 - and create another file
   - vi variable.tf --and search google variable.tf accesskey secretkey and copy

------------------
- **variable.tf**
----------------
- variable "instance_type" {
   - description = "Instance type t2.micro"
   - type        = string
   - default     = "t2.micro"
- }

3. file3--and create  another file
   - vi main.tf ---and search google main.tf
----------------------
- **main.tf**
-----------------------
- resource "aws_instance" "ec2_example" {
   - ami           = "ami-06a0b4e3b7eb7a300"
   - instance_type =  var.instance_type

   - tags = {
           - Name = "variable"
   - }
- } 

5. innatiated the terraform
   - terraform init
6. validate the terraform
   - terraform validate
7. terraform apply
   - terraform apply 

------------------------------
**DAY-20 (14-02-2022)**
- [DAY-20_VIDEO LINK](https://www.youtube.com/watch?v=IRkcq94BZIQ)
- **TOPICS DISCUSSED ON 14/02/2022**
  - REFERENCE:-
  - https://learn.hashicorp.com/tutorials/terraform/variables
- Topic variables
1. first we launch the ubantu server 20.04
2. connect to git bash using ssh key
   - convert to root user: sudo -i
   - update:sudo apt-get update
3. install terraform in ubantu 20.04:-
- Repository Configuration:
  - curl -fsSL https://apt.releases.hashicorp.com/gpg | sudo apt-key add -
  - sudo apt-add-repository "deb [arch=$(dpkg --print-architecture)] https://apt.releases.hashicorp.com $(lsb_release -cs) main"
  - sudo apt install terraform
- Choosing Terraform Versions:
  - apt policy terraform
  - sudo apt install terraform=0.14.0
- check the version:
  - terraform --version
4. terraform to be configured for aws account
   - choose iam accpunt and select the manage access keys--
   - create new access key
- connect to access keys and seceret keys
1. file1 - first we create a file using .tf extension
  - vi provider.tf
  - goto google search provider.tf and copy the
--------------------
- **provider.tf**
-----------------
1. provider "aws" {
2.   region     = "var.aws_region"
3.   access_key = "var.access_key"
4.  secret_key = "var.access_key"
5. }

2. file2 - and create another file
   - vi variable.tf --and search google variable.tf accesskey secretkey and copy
------------------
- **variable.tf**
----------------
1. variable "aws_region"    {
2.   description ="aws region"
3.   typr        =string
4.   default     ="ap-south-1"
5. }

6. variable "access_key"    {
7.  description ="access key"
8.   typr        =string
9. default     ="AKIAUJ5V5GF7WEYIBSXD"
10. }

11. variable "secret_key"    {
12.   description ="secret key"
13.   typr        =string
14.   default     ="5K/xRE+jJ3+o8Yg0uF9fPIFNbkKFb3GB/xgEodkJ"
15. }

16. variable "instance_type" {
17.   description = "Instance type t2.micro"
18.   type        = string
19.   default     = "t2.micro"
20. }

3. file3--and create  another file
   - vi main.tf ---and search google main.tf
----------------------
- **main.tf**
-----------------------
1. resource "aws_instance" "ec2_example" {
2.   ami           = "ami-06a0b4e3b7eb7a300"
3.   instance_type =  var.instance_type
4.   tags = {
5.           Name = "variable"
6.   }
7. } 
----------------------
5. innatiated the terraform
   - terraform init
6. validate the terraform
   - terraform validate
7. terraform apply
   - terraform apply 

--------------------------------------------------------------------------------------------------------
**DAY-21 (16-02-2022)**
- [DAY-21_VIDEO LINK](https://youtu.be/IMjAN0ucdng)
- **TOPICS DISCUSSED ON 16/02/2022**
  - creation vpc using terraform in visual studio code

------------------------------------------------------------------------------------------------------------------------------
**DAY-22 (17-02-2022)**
- [DAY-22_VIDEO LINK](https://youtu.be/uFh87rc_JwU)
- **TOPICS DISCUSSED ON 17/02/2022**
  - creatinng vpc ,public subnets,private subnets,internet gateway,route table using terraform in visual studio

-------------------------------------------------------------------------------------------------------------------------------------------------
**DAY-23 (22-02-2022)**
- [DAY-23_VIDEO LINK](https://youtu.be/nMSI0VInCOQ)
- **TOPICS DISCUSSED ON 22/02/2022**
- **docker**
  1. Docker Engine
  2. Images and Image Management
  3. Networking
  4. Storage and Volumes
  5. Security
- docker engine:
  - docker engine->rest api->docker daemon (images,volumes,networks)->containerd (managing containers)->containend-shim->runc(run containers)->lib container - namesspaces,cgroups

- installation 3 ways:
1. convience script ()
2. binaries (installing from packages)
3. repo

docker comes with 2 version
1. community version
2. enterprise version
-----------------------
1. **convience script ()**
   - goto google search get.docker.com
----------------------------
2. **binaries (installing from packages)**
   - goto google search dowload.docker.com
   - it is showing 3 operating systems
     - linux/
     - mac/
     - win/
--------------------------------------
3. **repo**
    - yum install yum-utsis -y
    - yum repolist
  - config:
    - yum -config-manager --add-repo https://dowload.docker.com/linux/centos/docker-ce.repo
  - check the repo available or not:
    - yum repolist
    - yum install docker-ce docker-ce-cli containerd.io -y

-------------------------------------------------------------------------------------------------------------------------------------------------
**day-24 (24-02-2022)**
- [DAY-24_VIDEO LINK](https://youtu.be/LemcWBWbcgE)
- **TOPICS DISCUSSED ON 24/02/2022**
  - **GIT**

------------------------------------------------------------------------------------------------------------------------------------------------------------
**day-25 (25-02-2022)**
- [DAY-25_VIDEO LINK](https://youtu.be/Vn5_gu_f0xI)
- **TOPICS DISCUSSED ON 25/02/2022**
 - **git:-**
   - working directory->staging area ->local reposratory->remote reposratory
   - first we launch the ubantu server 20.0.4
   - and connect to the github and install the git in server
 - check the files->  ls -all
 - creating a repostratiry in github
 - git clone (git ssh url)
 - open the file->cd feb25/
   - creating files current directory->vi test1
   - creating files current directory->vi test2
   - creating files current directory->vi test3
   - creating files current directory->vi test4
 - git connert to unstaging area to staging area
   - git add .
   - or
   - git add test1,test2,test3,test4
   - git config --global user.name "MANI3415"
 - check the user name:
   - git config user.name
- git commit message:
   - git commit -m "intial commit1"
- git push command:
   - git push origin main 
   - asking the user.name-->MANI3415
   - asking the password-->using tocken id
- finally the test files are pushing the github

- **Maven:-**

- Maven->Maven is a powerful project management tool that is based on PDM(project object model) used for project build,depependency and documentation
- **maven life cycle**
  1. validate
  2. compiler
  3. test
  4. package
  5. integration test
  6. verify
  7. install
  8. deploy

- **install maven in ubantu 20.0.4**
  - sudo apt update
  - sudo apt install maven
  - mvn -version
- create the pom.xml file
  - vi pom.xml
------------------------------------------
```<project xmlns="http://maven.apache.org/POM/4.0.0"   
xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"  
  xsi:schemaLocation="http://maven.apache.org/POM/4.0.0   
http://maven.apache.org/xsd/maven-4.0.0.xsd">  
  
  <modelVersion>4.0.0</modelVersion>  
  
  <groupId>com.javatpoint.application1</groupId>  
  <artifactId>my-application1</artifactId>  
  <version>1.0</version>  
  <packaging>jar</packaging>  
  
  <name>Maven Quick Start Archetype</name>  
  <url>http://maven.apache.org</url>  
  
  <dependencies>  
    <dependency>  
      <groupId>junit</groupId>  
      <artifactId>junit</artifactId>  
      <version>4.8.2</version>  
      <scope>test</scope>  
    </dependency>  
  </dependencies>  
  
</project>  
```
--------------------------------------
  - mvn validate
  - mvn compile
  - mvn test
  - mvn package
  
--------------------------------------------------------------------------------------------------------------------------------------
**DAY-26 (26-02-2022)**
- [DAY-26_VIDEO LINK](https://youtu.be/oZzWgYcpcbo)
- **TOPICS DISCUSSED ON 26/02/2022**
  - **jankins:**
  - it is continuous integreation and automation tool running
  - first we launch the ubantu 20.0.4 server and connect to gitbash
    - install jankins in ubantu 20.0.4
    - Use to Long Term Support release
- **Step 1 — Installing Jenkins:**
```
curl -fsSL https://pkg.jenkins.io/debian-stable/jenkins.io.key | sudo tee \
  /usr/share/keyrings/jenkins-keyring.asc > /dev/null
echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] \
  https://pkg.jenkins.io/debian-stable binary/ | sudo tee \
  /etc/apt/sources.list.d/jenkins.list > /dev/null
sudo apt-get update
sudo apt-get install jenkins
```
- **step 2**
  - ls -all
  - sudo cat /var/lib/jenkins/secrets/initialAdminPassword

- **step 3 — Opening the Firewall:**
  - enable the port 8080
  - goto security groups->inbound rules->all tcp-anywhere->save
- **Step 4 — Setting Up Jenkins:**
  - http://your_server_ip_or_domain:8080
  - Copy the 32-character alphanumeric password from the terminal and paste it into the Administrator password field, then click Continue.

-------------------------------------------------------------------------------------------------------------------------------------------------
**DAY-27 (28-02-2022)**
- [DAY-27_VIDEO LINK](https://www.youtube.com/watch?v=5H9esO6xNfo)
- **TOPICS DISCUSSED ON 28/02/2022**
   - **jankins pipeline**
     - first we launch the server and install the jenkins in server
     - http://your_server_ip_or_domain:8080
     - Copy the 32-character alphanumeric password from the terminal and paste it into the Administrator password field, then click Continue.
   - [groovy reference](https://www.guru99.com/groovy-tutorial.html)
   - **example:1**
     - select pipeline->ok
     - Goto advanced project options->select hello word>save
     - build the code
     - console output->check the output
   - **example:2**
     - select pipeline->ok
     - Goto advanced project options->select scripted pipeline-ok
     - build the code
   - [Examples of Bash Script](https://linuxhint.com/30_bash_script_examples/)
   - **example:3**
     - select pipeline->ok
     - Goto advanced project options->SCM->SELECT GIT (IT IS RUNNING SOURCE CODE MANAGEMENT)->Give the Repository URL->ok
   - **Manage jenkins:**
      - config system
      - global tool configuration
      - manage plugins
      - manage nodes and clouds  
  
-------------------------------------------------------------------------------------------------------------------------------------------------
**DAY-28 (04-03-2022)**
- [DAY-28_VIDEO LINK](https://www.youtube.com/watch?v=2vMHy8fCm3Y)
- **TOPICS DISCUSSED ON 04/03/2022**  
  - **ANSIBLE**
     - it is a configuration tool management 
     - playbooks
     - ansible -i playbook example.yml
  - [ansible pic](https://1.cms.s81c.com/sites/default/files/2018-11-22/Ansible_ov.png)
  - [playbook examples](https://docs.ansible.com/ansible/latest/network/getting_started/first_playbook.html)
  - **Ansible install:**
    -[Ansible_install_ubantu_server-20.0.4_reference](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)
 ```
 sudo apt update
$ sudo apt install software-properties-common
$ sudo add-apt-repository --yes --update ppa:ansible/ansible
$ sudo apt install ansible
```
- [Ansible_github_link_reference](https://github.com/rawi24/ansible2)
  
--------------------------------------------------------------------------------------------------------------------------------------------------
**DAY-29 (05-03-2022)**
- [DAY-29_VIDEO LINK](https://www.youtube.com/watch?v=239hQ1bcjjk)
- **TOPICS DISCUSSED ON 05/03/2022**  
  - **ANSIBLE**
  - **Navigate to One swrver to another server using configuration**
    - First we launch the 2 servers (ubantu-20.0.4)
    - connect to  gitbash
  - create a user in server1 
    - adduser devops  
    - add the password
  - create a user in server2
    - adduser devops  
    - add the password
  - connect server1 to server2 
    - ssh devops@server2_publicip
    - it is showing authentication delined
  - secureshall configuration:server1
    - vi/etc/ssh/sshd_config
      - passwordauthentication change no to yes
      - save & quit (:wq!)
  - secureshall configuration:server2
    - vi/etc/ssh/sshd_config
      - passwordauthentication change no to yes
      - save & quit (:wq!)
  - restart the service (server1 & server2)
    - service ssh restart 
  - connect server1 to server2
    - ssh devops@server2_publicip
    - give the password
    - now it is secureshall is showing the private ip of server2
    - exit
  - connect server2 to server1
    - ssh devops@server1_publicip
    - give the password
    - now it is secureshall is showing the private ip of server1
    - exit
   
   - **without password authentication**
    - access the sudo permissions:server1
       - vi/etc/sudoers
         - give the configuration:
         - devops ALL =(ALL:ALL) NOPASSWD:ALL 
         - save & quit (:wq!)
    - access the sudo permissions:server2
       - vi/etc/sudoers
         - give the configuration:
         - devops ALL =(ALL:ALL) NOPASSWD:ALL 
         - save & quit (:wq!)
    - remove the ssh directory (server1 & server2)
       -  ls -all
       -  rm -rf .ssh/
    - now it's create a secureshall (server1)
       - ssh-keygen
       - now it's copy the ssh key
       - ssh-copy-id devops@server2_publicip
    - connect server1 to server2 withoutpassword
      - ssh devops@server2_publicip
    - now it's create a secureshall (server2)
       - ssh-keygen
       - now it's copy the ssh key
       - ssh-copy-id devops@server1_publicip
    - connect server2 to server1 withoutpassword
      - ssh devops@server1_publicip

- **Ansible install:**(server1)
    -[Ansible_install_ubantu_server-20.0.4_reference](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)
 ```
 sudo apt update
$ sudo apt install software-properties-common
$ sudo add-apt-repository --yes --update ppa:ansible/ansible
$ sudo apt install ansible
```
- check the version
  - ansible --version
- config:(server1)
  - sudo vi /etc/ansible/hosts
    -  give the server2_publicip
    -  save & quit (:wq!)
  - remove the ssh directory (server1 & server2)
       -  ls -all
       -  rm -rf .ssh/
  - now it's create a secureshall (server1)
       - ssh-keygen
       - now it's copy the ssh key
       - ssh-copy-id devops@server2_publicip
  - ansible -m ping all
  - ssh devops@server2_publicip
  - create test1 file
     - mkdir test1
  - open the file
     -  cd test1/
     -  vi hosts
        - copy the server2_publicip
     - ansible -i hosts -m ping all
  
  ---------------------------------------------------------------------------------------------------------------------------------------------------------------------
  
