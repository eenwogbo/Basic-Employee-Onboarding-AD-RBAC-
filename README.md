# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
* A fast growing, fictional company called Northstar Medical Group was growing fast and needed some structure with Identity & Access Management. They had no RBAC, Users were assigned access AD-HOC, no audit trails, and HIPPA risks.

## Solution Overview
* The solution was to build out a basic employee onboarding pipeline in Active Directory. I created OUs based on each department, created security groups, and used the RBAC method to give users access ONLY according to their role. 

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
* Solved a mock ticket where user was given the incorrect access
* I fully documented my steps end-to-end

