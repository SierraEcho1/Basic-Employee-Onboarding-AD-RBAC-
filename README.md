# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
Northstar Medical Group is a growing fictional healthcare organization that has relied on a Managed Service Provider (MSP) for IT support for several years, resulting in poorly managed infrastructure and no standardized IT practices. User accounts, access permissions, and administrative processes are inconsistent and lack centralized management, and manual processes with no defined policies increase the risk of unauthorized access and inadequate auditing. These deficiencies also create potential HIPAA compliance risks, particularly regarding the protection of sensitive patient information. I was brought on to design and implement a structured IT infrastructure using Active Directory to centralize identity management, standardize access controls, and establish a stronger security foundation.

## Solution Overview
I built a functional Active Directory lab in a virtualized environment and established the NMG.com domain to provide Northstar Medical Group with centralized identity and access management. I designed a structured Organizational Unit (OU) hierarchy for Finance, HR, IT, and Operations, supported by security groups and a Role-Based Access Control (RBAC) model to organize permissions according to job responsibilities. I created and configured 15 user accounts, applying controlled access assignments to support consistent account provisioning and reduce the risk of unauthorized access. During testing, I investigated an incident ticket involving Jane Cooper, whose account had been incorrectly assigned to the Operations department instead of HR. I identified the misconfiguration, corrected her account placement, verified the resolution, and documented the incident to reinforce proper troubleshooting and IT documentation practices. These implementations established a more organized, secure, and manageable identity infrastructure for Northstar Medical Group.

## Video Walkthrough
www.totalthreatdemovideo.com 

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
* Established the NMG.com domain in a virtualized lab and designed a structured Organizational Unit (OU) structure for Finance, HR, IT and Operations.
* Created and configured 15 user accounts, organized departmental security groups, and applied role-based-access control.  
* Investigated and corrected a user account placement error involving an employee incorrectly assigned to Operations instead of HR, verified the correction, and documented the resolution.
