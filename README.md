# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
I was brought on by Northstar Medical Group during a period when inconsistent user accounts were being mismanaged by MSP. The existing environment lacked structure approach to user organization and security. This created a compliance risk with HIPPA, which could lead to potentially large fines due to the infrastructure not meeting standards. 

## Solution Overview
I implemented a more organized Active Directory structure by creating Organizational Units (OUs) for Northstar Medical Group to organize users by department, ensuring proper administrative structure and access management. I then created department-specific security groups to simplify permission management and enforce role-based access control.
Each security group serves as a centralized method for assigning permissions, allowing only authorized members to access the resources required for their respective departments. Departmental resources remain isolated, preventing unauthorized access across departments without the appropriate permissions.
Finally, I verified that all users were assigned to the correct security groups based on the provided requirements, ensuring accurate access control and compliance with the organization’s security policies.

## Video Walkthrough
[Add your video walkthrough link placeholder here. You will record this tomorrow and update this link so visitors can see a live demonstration of your lab environment.]

## Tools Used
* Windows Server
* Active Directory Domain Services
* VirtualBox
* UTM
* RBAC
* GitHub

## Project Timeline
* Day 1: Domain creation and domain controller promotion
* Day 2: Organizational unit and security group design
* Day 3: User provisioning and RBAC implementation
* Day 4: Incident response and resolution (NMG-0047)
* Day 5: Documentation and case study packaging

## Key Accomplishments
* Built NMG.com domain from scratch
* Designed department-based OU structure
* Provisioned 15 user accounts with consistent naming conventions and attribute standards
* Diagnosed and resolved a multi-cause access issue (wrong OU + missing group membership)
* Documented full incident resolution with root cause analysis
