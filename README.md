# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
I was hired at NorthStar due to the MSP mismanagement, which created lack of structure,and inconsistent permissions. This was a problem would caused an issue with HIPAA and it posed high risks. These high risks could lead to large fines due to compliance issues.

## Solution Overview
I created OU's (Finance, IT, HR, Operations) to organize each user by department to ensure they have the correct permissions. I then created security groups as a container for each user, which allows what access they are granted. For eacj securirty group only the users apart will be able to gain resources as needed per the department. Each department is a seperate entty and another department does not allow for access to another. I confirmed all users were assigned to correct security groups per the information provided. 

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
