DEVOPS--CLASSLINK
- Zoom Link:https://zoom.us/j/96078845638?pwd=dEZzSTBhQUtJNnR3VndtUDVYL1M1Zz09 
- Zoom Credentials: Zoom id: 960 7884 5638
- Passcode: devops
----------------------------------------------------------------------------------------------------
**DAY-1 (18-01-2022)
- VIDEO LINK:https://www.youtube.com/watch?v=d3u72SxI7ZE&t=445s
- TOPICS DISCUSSED ON 18/01/2022
  - DEVOPS INTRODUCTION

--------------------------------------------------------------------------------------------------
**DAY-2 (19-01-2022)
- VIDEO LINK:https:https://www.youtube.com/watch?v=n4tlrIbEbPs
- TOPICS DISCUSSED ON 19/01/2022
  - LINUX COMMANDS DISCUSSED

----------------------------------------------------------------------------------------------------
**DAY-3 (20-01-2022)
- VIDEO LINK:https:https://www.youtube.com/watch?v=xN1I4MTWbZo
- TOPICS DISCUSSED ON 20/01/2022
  - LINUX COMMANDS DISCUSSED

-----------------------------------------------------------------------------------------------------
**DAY-4 (21-01-2022)
- VIDEO LINK:https:https://www.youtube.com/watch?v=vN3JCmrT9GA
- TOPICS DISCUSSED ON 21/01/2022
  - DEVOPS TOOLS
    - AWS
    - GITHUB
    - DOCKER
    - ANCIBLE
    - KUBER NETES
    - MAVEN
    - JANKINS
    - SPLUNK
  - AWS ACCOUNT CREATION
  - DEMO OF EC2(SERVER LAUNCH)

-----------------------------------------------------------------------------------------------------
**DAY-5 (24-01-2022)
- VIDEO LINK:https://www.youtube.com/watch?v=zho0BsWVU6M
- TOPICS DISCUSSED ON 24/01/2022:
  - EC2(SERVER LAUNCH)
  - SECURITY GROUPS

------------------------------------------------------------------------------------------------------
**DAY-6 (25-01-2022)
- VIDEO LINK:https://www.youtube.com/watch?v=qRrpPEus0go&t=2933s
- TOPICS DISCUSSED ON 25/0/2022:
  - IAM(IDENTITY ACCESS MANAGEMENT)
  - MFA(MULTI FACTOR AUTHANTICATION)
    - DASHBOARD
    - USER--CREATE USER
    - ROLES--CREATE RULES(HOW MANY SERVICES ARE YOU NEED)
    - POLICES--CREATE POLICES(SERVER ACCESSABILITY TIME EXAMPLE:SOMETIMES SERVER ACCESSABILITY INCREASED AND SOMETIME LOW)
    - IDENTITY PRIVIDER

-----------------------------------------------------------------------------------------------------
**DAY-7 (27-01-2022)
- VIDEO LINK:https://www.youtube.com/watch?v=ZuI3sB7FUho
- TOPICS DISCUSSED ON 27/01/2022
  - S3BUCKET(SIMPLE STORAGE SERVICE)
  - IT IS STORE THE FILES RANGE(0-5GB)
  - UPLOADING FILE IN S3BUCKET AND ACCESS 

------------------------------------------------------------------------------------------------------
**DAY-8 (28/0/2022)
- VIDEO LINK:https://youtu.be/klHKLSLHObI
- TOPICS DISCUSSED ON 28/01/2022
  - S3 BUCKET
  - LOAD BALANCING
  - CREATING VPC(VIRTUAL PRIVATE CLOUD):
    - IP ADDRESSES
    - SUBNETS
    - ROUTING
    - INTERNET GATEWAY

------------------------------------------------------------------------------------------------------
**DAY-9 (29-01-2022)
- VIDEO LINK:https://youtu.be/vuSYOf9-_dM
- Topics discussed on 29/1/2022:
  - VPC Creation
  - Subnet Creation
  - Routing Table Creation
  - Attaching the same to internet gateway
  - discussed about Public DNA
  - discussed about Public VPC
  - Deleting the created VPC

**step by step launch ec2 by using created vpc
  
- step-1

openvpc
---------
yourvpcs
----------
create vpc--vpcname--ipv4-10.0.0.0/16-create vpc--actions-editdnshostname--enable--save changes

- step-2

subnets
-------
create subnet--given already created vpc id--subnet name--any one select availability zone--ipv4-10.0.0.0/16--create subnet

- step-3

internet gateway
-----------------
create internet gateway--name--create internet gateway--actions--attach to vpc--given already created vpc id--give ok

- step-4

route table
-------------
alredy one route table alredy created--select the name--routes--edit routes--add route--0.0.0.0/0--select internet gateway--select the alredy created gate way--save changes
select sunnet associate--select edit subnet associate--select given one--ok

- step-5
open ec2
------------
launche instance--select any one of ami--select t2 micro free trair--choose instance type---select the alredy create vpc-to launch the ec2--open git bash to connection--now ec2 is launched by using created vpc
without any error.

------------------------------------------------------------------------------------------------------------------------------
**DAY-10 (31-01-2022)
- VIDEO LINK:https://youtu.be/EFZzknfFXsg
- Topics discussed on 31/1/2022:




-------------------------------------------------------------------------------------------------------------------------------
**DAY-11 (01-02-2022)
- VIDEO LINK:https://youtu.be/HaQvaEP2SJ8
- TOPICS DISCUSSED ON 01/02/2022:
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

           EFS(Elastic File System)

### Network Load Balancer is a Faster Then Application Load Balancer

**NETWORK LOAD BALANCER
- NLB IS WORKS ON TCP/UDP PROTOCOL
- OSI LAYER
- PORT BASED ROUTING

**APPLICATION LOAD BALANCER:
- ALB------HTTP/HTTPS
- APPLICATION LAYER
- PATH BASED ROUTING

---------------------------------------------------------------------------------------------------------------------------------
**DAY-12 (02-02-2022)
- VIDEO LINK:https://www.youtube.com/watch?v=eA0N_elaO7I
- TOPICS DISCUSSED ON 02/02/2022

- first we launch the EC2 Instances

- load balancing
    - Load Balancers             
    - Target Groups

- STEP-1:-
                                - FIRST WE CREATING TARGET GROUPS:-

   - CREATE TARGET GROUPS FOLLOW THE APPICATION LOAD BALANCER PROTOCOL(HTTP/HTTPS)
   - SELECT TARGET GROUPS-CREATE TARGET GROUPS--GIVE THE TARGET NAME AND SELECT APPLICATION LOAD BALANCER PROTOCOL--AND SELECT TO REGISTER TARGETS INSTANCES--INCLUDE AS PENDING      BELOW--CREATE TARGET GROUP
 
   - CREATE TARGET GROUPS FOLLOW THE NETWORK LOAD BALANCER PROTOCOL(TCP/UDP/TLS)
   - SELECT TARGET GROUPS-CREATE TARGET GROUPS--GIVE THE TARGET NAME AND SELECT NETWORK LOAD BALANCER PROTOCOL--AND SELECT TO REGISTER TARGETS INSTANCES--INCLUDE AS PENDING          BELOW--CREATE TARGET GROUP

- STEP-2:-
                                        - LOAD BALANCERS:-
  - ALB CREATION:-
    - SELECT CREATE LOAD BALANCER--SELECT APPLICATION LOAD BALANCER--GIVE THE LOAD BALANCER NAME AND SELECT THE ALP TARGET GROUP--CREATE LOAD BALANCER
  - NLB CREATION:-
    - SELECT CREATE LOAD BALANCER--SELECT NETWORK LOAD BALANCER--GIVE THE LOAD BALANCER NAME AND SELECT THE NLB TARGET GROUP--CREATE LOAD BALANCER

- Auto Scaling
    - Launch Configurations
    - Auto Scaling Groups

- STEP-3:-
                                     - Launch Configurations:-
  
  -- Select the Launch Configurations create Launch Configurations--first we create the launch templates--and give the template name and select AMI(amazon machine image)--and        select any one of security group--create launch template
   - now create Launch Configurations--give name,select any one of AMI and select instance(t2-micro),and select key pair is requried or not--create Launch Configurations

- STEP-4:-
                                      - Auto Scaling Groups:-

  -- Select Auto Scaling Groups--Create Auto Scaling Groups--

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
 **DAY-12 (03-02-2022)
- VIDEO LINK:
- TOPICS DISCUSSED ON 03/02/2022



