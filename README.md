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

<img width="1920" height="1080" alt="Screenshot 2026-10-30 083846" src="https://github.com/user-attachments/assets/b2887a2e-ee15-4937-bee0-2a17d3b7dfe3" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 093424" src="https://github.com/user-attachments/assets/0df74b44-474f-490d-9f3a-22bbe09a5289" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 092044" src="https://github.com/user-attachments/assets/8d56fd03-2c05-43f5-8146-5c34a14a4aa4" />
<img width="948" height="1078" alt="Screenshot 2026-10-30 091803" src="https://github.com/user-attachments/assets/44454eb0-4f62-4e1d-b4b6-798e920deb98" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 091543" src="https://github.com/user-attachments/assets/dcc7cc23-9662-4b51-9bb0-f1cbe36effc8" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 090727" src="https://github.com/user-attachments/assets/4839f7d5-e022-4c93-9e19-6d4fd10b596d" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 090642" src="https://github.com/user-attachments/assets/af13d799-0790-4ebb-abae-065b35084ed2" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 090331" src="https://github.com/user-attachments/assets/73f792db-4eae-42c7-9b66-af3714dded5a" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 090021" src="https://github.com/user-attachments/assets/5300cff7-59f2-4380-8083-a7e767864c2f" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 085823" src="https://github.com/user-attachments/assets/715e9c9f-2f58-4dfd-8f2c-8199cb95bf3f" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 085603" src="https://github.com/user-attachments/assets/ea1baa3f-e696-4805-8d4c-2d1c38b853c9" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 085540" src="https://github.com/user-attachments/assets/39dccba7-faa9-4fe9-9b46-dda3e2158029" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 085356" src="https://github.com/user-attachments/assets/4f7286ae-2099-4fa7-a17f-77f248965ddd" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 085306" src="https://github.com/user-attachments/assets/194e5d25-e860-41d9-beef-7bf11d8558f4" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 085202" src="https://github.com/user-attachments/assets/e5e9a23f-8f55-4fd4-bd22-ac0259aeae1a" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 085055" src="https://github.com/user-attachments/assets/bb97a108-c5a2-4d22-8df2-846585e85bb3" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 084235" src="https://github.com/user-attachments/assets/d760053a-8b61-4250-8d9c-26331ef455fe" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 084125" src="https://github.com/user-attachments/assets/6809ada5-08d7-405c-8c91-8ac27c70eeb0" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 083920" src="https://github.com/user-attachments/assets/2603e988-66ba-4a40-993e-d0a2c454936e" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 083858" src="https://github.com/user-attachments/assets/90e0040b-0e6c-496e-9275-148e55a4faee" />
<img width="1920" height="1080" alt="Screenshot 2026-10-30 083920" src="https://github.com/user-attachments/assets/2e3b458f-c20b-4511-a9f2-69aac9c9d789" />



# Result:
Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) - instance has been successfully created and launched in AWS
