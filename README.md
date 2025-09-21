# CLOUD-STORAGE-CREATION-S3-AND-LAUNCHING-AN-EC2-INSTANCE-IN-AWS-

# Name:VASANTH S
# Register Number:212222110052

# AIM :
To create an AWS account, set up a root user, and create an IAM user with specified permissions.

# PROBLEM STATEMENT :
This experiment involves creating an AWS account, configuring security settings for the root user, and setting up an IAM user. IAM users allow for secure, managed access to AWS resources without exposing the main account's root credentials.

# Procedure:
# Sign in to the AWS Management Console: 
Go to the AWS Management Console and log in with your AWS credentials.
# Navigate to the EC2 Dashboard: 
Once logged in, locate and click on the "EC2" service in the AWS Management Console.
# Launch an Instance: 
On the EC2 dashboard, click the "Launch Instance" button.
# Choose an AMI (Amazon Machine Image):
Select the operating system and software you want to use for your instance (e.g., Amazon Linux, Ubuntu, Windows). • Click "Select" to choose the AMI.
# Choose an Instance Type:
Select the type of instance you need (e.g., t2.micro, m5.large) based on your workload requirements. • Click "Next: Configure Instance Details".
# Configure Instance Details:
Set the number of instances to launch, the availability zone, and other optional settings like networking and security. • Click "Next: Add Storage".
# Configure Storage:
Specify the size and type of storage for your instance. • Click "Next: Add Tags".
# Add Tags (Optional):
Add tags to your instance for easier identification and management. • Click "Next: Configure Security Group".
# Configure Security Group:
• Choose or create a security group to control inbound and outbound traffic to your instance. • Click "Review and Launch".
# Review and Launch:
• Review all the configurations and click "Launch".
# Create a Key Pair (if you haven't already): 
You'll be prompted to create a new key pair or choose an existing one. • Download the key pair (.pem file) and store it securely.
# Launch the Instance:
Click "Launch Instance" to start the instance creation process.
# Connect to your Instance:
• Once the instance is running, you can connect to it using SSH (for Linux) or RDP (for Windows). • Use the key pair you downloaded earlier to connect.

# output
<img width="1349" height="672" alt="Screenshot 2025-09-21 220431" src="https://github.com/user-attachments/assets/707e2640-dd04-4f76-b476-3f4dd64827e4" />

<img width="1342" height="680" alt="Screenshot 2025-09-21 222809" src="https://github.com/user-attachments/assets/18da8224-9739-4ba9-a8fe-002befa587c3" />

<img width="1362" height="682" alt="Screenshot 2025-09-21 222925" src="https://github.com/user-attachments/assets/fbbcdbac-952e-4cd4-bb4f-a15198deda87" />


 # RESULT
The AWS account was successfully created, with set up for the root user . Additionally, an IAM user was created with specified permissions, allowing for secure, controlled access to AWS resources without the use of the root account.
