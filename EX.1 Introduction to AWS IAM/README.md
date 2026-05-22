# Lab 1 - Introduction to AWS Identity and Access Management (IAM)
# NAME : SUBASHREE KARTHIKEYAN
# REG NO: 212224050049

## Title
Introduction to AWS Identity and Access Management (IAM)


## Objective
The objective of this lab is to understand how AWS Identity and Access Management (IAM) controls authentication and authorization in AWS. The lab focuses on exploring IAM users and groups, analyzing attached policies, assigning users to appropriate groups based on organizational roles, and validating permissions by testing service access.


## Prerequisites
- Basic understanding of cloud computing concepts  
- AWS Academy Lab access  
- Web browser with internet connectivity  


## Tools Used
- AWS Management Console  
- AWS Identity and Access Management (IAM)  
- Amazon EC2  
- Amazon S3  


## Tasks Performed

### Task 1: Explore IAM Users and Groups
- Reviewed pre-created IAM users: user-1, user-2, user-3  
- Explored IAM groups: EC2-Admin, EC2-Support, S3-Support  
- Inspected managed and inline policies attached to groups  
**Screenshot:**  
  <img width="1600" height="847" alt="594573068-2477f34e-7fdf-4670-8b5c-271a21df01ab" src="https://github.com/user-attachments/assets/01e5001d-fbd5-423d-b5b7-5772ae8ebbf1" />


### Task 2: Add Users to Groups
- Added user-1 to the S3-Support group  
- Added user-2 to the EC2-Support group  
- Added user-3 to the EC2-Admin group  
**Screenshot:**  
<img width="1600" height="730" alt="594573201-b9f59e23-561d-4f3e-8b8d-61a8962e529a" src="https://github.com/user-attachments/assets/2995887a-7083-4f48-9ef8-706ae1cc4cdd" />


### Task 3: Test IAM User Permissions
- Logged in using IAM sign-in URL  
- Verified S3 access for user-1  
- Verified EC2 read-only access for user-2  
- Verified EC2 administrative access for user-3  
**Screenshot:**  
<img width="1600" height="720" alt="594573283-2ad32dd8-fdb0-4b3e-8496-53919041ce0a" src="https://github.com/user-attachments/assets/461cab38-1194-4d1d-8d1f-feb32e5d6c43" />



## Workflow
1. Accessed IAM console and reviewed users and groups.  
2. Inspected policy permissions attached to groups.  
3. Assigned users to groups based on their roles.  
4. Logged in as each IAM user using the sign-in URL.  
5. Validated permissions by accessing AWS services.  


## Learning Outcomes
- Understood the role of IAM in AWS security.  
- Learned how IAM users, groups, and policies interact.  
- Gained practical experience implementing role-based access control.  
- Verified permission enforcement through real-time service testing.  


## Conclusion
This lab provided hands-on experience with AWS IAM by demonstrating how organizations manage secure access to cloud resources. Assigning users to groups with predefined policies simplified permission management and ensured role-based access control across AWS services.


## Author
**Name:** SUBASHREE KARTHIKEYAN
**Course:** Introduction to Cloud Computing  

