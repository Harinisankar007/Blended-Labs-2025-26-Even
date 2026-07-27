# Lab 1 - Introduction to AWS Identity and Access Management (IAM)

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
<img width="1600" height="910" alt="WhatsApp Image 2026-07-27 at 14 06 49" src="https://github.com/user-attachments/assets/efafd11f-0cb2-4be8-8d52-cb82113b1686" />

 <img width="1600" height="930" alt="WhatsApp Image 2026-07-27 at 14 06 54" src="https://github.com/user-attachments/assets/41c25de5-3029-4778-b1dc-02e707cde524" />


### Task 2: Add Users to Groups
- Added user-1 to the S3-Support group  
- Added user-2 to the EC2-Support group  
- Added user-3 to the EC2-Admin group  
**Screenshot:**
 <img width="1600" height="931" alt="WhatsApp Image 2026-07-27 at 14 11 04" src="https://github.com/user-attachments/assets/6bd8cab3-992d-4a7b-b761-eedcab94e037" />

 <img width="1600" height="927" alt="WhatsApp Image 2026-07-27 at 14 18 59" src="https://github.com/user-attachments/assets/6bd8d24d-91f7-4114-b391-a326fff7c5d4" />



 
  

### Task 3: Test IAM User Permissions
- Logged in using IAM sign-in URL  
- Verified S3 access for user-1  
- Verified EC2 read-only access for user-2  
- Verified EC2 administrative access for user-3  
**Screenshot:**  
<img width="1600" height="927" alt="WhatsApp Image 2026-07-27 at 14 22 59" src="https://github.com/user-attachments/assets/25e1d01f-08a7-4528-ab37-8f320f357195" />





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
**Name:** Your Name and (Reg No)
**Course:** Introduction to Cloud Computing  

