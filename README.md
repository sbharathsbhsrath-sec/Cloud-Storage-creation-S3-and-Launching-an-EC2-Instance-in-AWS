# EX:2-CLOUD-STORAGE-CREATION-S3-AND-LAUNCHING-AN-EC2-INSTANCE-IN-AWS-
## NAME:BHARATH S
## REGISTER NO:212225230031


# Aim: 
To create a Simple Storage Service (S3) in AWS and to launch an EC2 instance in AWS.

# Procedure
a) Steps to Create a first S3 Bucket:

Step 1: Sign in to the AWS Management Console Go to https://console.aws.amazon.com/s3. 

Step 2: Open the S3 Service In the console, type S3 in the search bar and select S3 to open the service dashboard. 

Step 3: Create Bucket Click the Create bucket button. 

Step 4: Configure Bucket Settings

• Bucket name: Choose a globally unique name. • AWS Region: Select the region where you want to store your data.

Step 5: Object Ownership Choose between: ▪ ACLs disabled (recommended) – Bucket owner has full control. ▪ ACLs enabled – Control access via access control lists.

Step 6: Block Public Access Settings By default, all public access is blocked. Leave it as-is unless you need public access. 

Step 7: Bucket Versioning (optional) Choose whether to enable versioning for objects in the bucket.

Step 8: Encryption (optional) Select encryption options (SSE-S3, SSE-KMS, or none). 

Step 9: Advanced Settings (optional) Add tags, configure logging, etc. 

Step 10: Create the Bucket Click Create bucket at the bottom of the page.

b) i. Steps to launch an EC2 Instance

Go to the EC2 Dashboard in AWS Console.

Click on “Launch Instance”.

Choose an Amazon Machine Image (AMI) (e.g., Amazon Linux).

Select an instance type (e.g., t2.micro for Free Tier).

Create or choose a key pair for SSH access.

Configure network settings (use default VPC/subnet).

Configure storage (default root volume is fine).

Review the settings and click “Launch Instance”.

Wait for the instance to enter the running state.

c) Step 3: Connect to Your Instance

• Linux: Use SSH command with your .pem key. • Windows: Use RDP with decrypted admin password.

d) Steps to Clean Up (Terminate the Instance)

Go to EC2 Instances.
Select your instance → Instance State → Terminate.

# Output:

## Simple Storage Service:
## EC2(Elastic Cloud Compute)
<img width="1920" height="1080" alt="Screenshot 2026-10-30 083846" src="https://github.com/user-attachments/assets/185c287b-115e-49e3-b5c4-eb7e561c13ff" />

<img width="1920" height="1080" alt="Screenshot 2026-10-30 083858" src="https://github.com/user-attachments/assets/7e9e9118-ff65-4d90-959c-e9fc39bf3a52" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 083846" src="https://github.com/user-attachments/assets/de90b3a4-a4d7-404e-b51c-cf19ef886116" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 083846" src="https://github.com/user-attachments/assets/6602f1e0-9b12-45ea-b1f4-045513ebfedf" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 093424" src="https://github.com/user-attachments/assets/62f6e866-1f19-4181-bc0b-9fa05be9b830" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 093424" src="https://github.com/user-attachments/assets/f63bf12a-9bf0-4bf5-8033-48398465d426" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 092044" src="https://github.com/user-attachments/assets/168433ce-7a3a-47e6-89c4-c9a59636af1d" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 092044" src="https://github.com/user-attachments/assets/fd53d45e-ccbf-46bb-9128-ceab0312b583" />
<img width="948" height="1078" alt="Screenshot 2026-10-30 091803" src="https://github.com/user-attachments/assets/9e9b77de-3ec8-4cc4-8c18-656dbb101476" />
<img width="948" height="1078" alt="Screenshot 2026-10-30 091803" src="https://github.com/user-attachments/assets/481091e9-ebe9-482d-ba98-ed0bfbaf1827" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 091543" src="https://github.com/user-attachments/assets/706671f3-5024-479e-af5a-b681e0a85653" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 091543" src="https://github.com/user-attachments/assets/afa62c5d-8244-44b4-aeb6-1adee6ba1df5" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 090727" src="https://github.com/user-attachments/assets/43a7b58c-6ced-4fa9-af52-eba205eb40b0" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 090727" src="https://github.com/user-attachments/assets/c55bc407-cc5e-466c-9672-2b4b7c340e7b" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 090642" src="https://github.com/user-attachments/assets/c9461d8c-5e4e-4cbd-ad50-f68d8836253a" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 090642" src="https://github.com/user-attachments/assets/5e2e2f28-f592-4b19-b274-463b67f21b4d" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 090331" src="https://github.com/user-attachments/assets/116ff0a5-0735-4d50-908c-634345f6569b" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 090331" src="https://github.com/user-attachments/assets/887b29ae-d78b-425a-9baf-559a14891146" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 090021" src="https://github.com/user-attachments/assets/25a73930-d722-4952-bf3d-9a79ff7779b0" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 090021" src="https://github.com/user-attachments/assets/e3629cf1-d84b-4a88-aa99-dd1fe869212d" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 085823" src="https://github.com/user-attachments/assets/b487d472-448e-4b72-8d46-725bad18ec42" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 085603" src="https://github.com/user-attachments/assets/44c324f3-7355-42fe-9e6e-8ccb6dc53cfd" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 085823" src="https://github.com/user-attachments/assets/52d62c3e-4881-4ebe-996d-8fc664effc2c" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 085540" src="https://github.com/user-attachments/assets/69daaf8e-8d48-4544-93f3-35e13487a21a" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 085356" src="https://github.com/user-attachments/assets/ae14d13d-ebf8-4402-8680-67a41534bdf4" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 085603" src="https://github.com/user-attachments/assets/9ecf6b98-72de-4e30-a53a-45ba3deaace1" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 085540" src="https://github.com/user-attachments/assets/d35422c3-2a0a-4bec-a26c-5ad59e7c633d" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 085356" src="https://github.com/user-attachments/assets/6423c21c-7538-419e-ac31-27e5677cf70b" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 085306" src="https://github.com/user-attachments/assets/37480962-2f81-44f8-aa59-26582d2b4e34" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 085202" src="https://github.com/user-attachments/assets/aac1aa0f-2f16-4663-b3ce-50356b58d8d9" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 085306" src="https://github.com/user-attachments/assets/c76013f4-c856-4622-8503-baef4fec3602" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 085055" src="https://github.com/user-attachments/assets/9e6bcaa7-cc1f-4f59-a2fc-19b32c3d44c9" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 085202" src="https://github.com/user-attachments/assets/2a23aa3c-8bad-49e9-92ab-a2d13ba8266d" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 084235" src="https://github.com/user-attachments/assets/084c798c-a7ac-4fab-a117-1af90328699d" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 085055" src="https://github.com/user-attachments/assets/bccf8cdf-82f9-4e4f-af6f-2b4fc13435b6" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 084125" src="https://github.com/user-attachments/assets/6607a78d-2276-4163-86c8-67ecfe5f3c07" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 084235" src="https://github.com/user-attachments/assets/408ebe51-d794-4aca-ab43-1a090f3ec5b3" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 084125" src="https://github.com/user-attachments/assets/0a5a45bc-8641-4d87-ae4c-f93adfe4830a" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 083920" src="https://github.com/user-attachments/assets/4a236ecf-3486-4c49-b323-c8bab9298578" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 083920" src="https://github.com/user-attachments/assets/4412945f-496c-45a4-961e-713943e4db63" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 083858" src="https://github.com/user-attachments/assets/d2b17500-5aed-4258-85a4-9c6b66bdd2c5" />




# Result:
Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) - instance has been successfully created and launched in AWS
