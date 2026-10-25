# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement

Before this project, Northstar Medical Group’s Active Directory environment was poorly organized and inconsistently managed by its former managed service provider (MSP). User accounts were created manually without a standard process, and there was little structure for organizing users, departments, or access. Permissions were inconsistent, and employee accounts were not always disabled promptly when someone left the organization. These gaps created security and operational risks and could make it difficult for Northstar to demonstrate appropriate access controls during a HIPAA-related review.

## Solution Overview

The project establishes a new Active Directory domain, **NMG.com**, as the foundation for Northstar’s identity infrastructure. Organizational units (OUs) provide a clear structure for organizing accounts and resources, such as by department and object type. Security groups are designed to assign access consistently, using a flat role-based access control (RBAC) model in which permissions are assigned to groups rather than directly to individual users. User provisioning follows a controlled, documented process intended to support least privilege and timely account changes. Together, these measures provide a more consistent and auditable approach to identity and access management; they support compliance efforts but do not, by themselves, guarantee HIPAA compliance.

## Video Walkthrough

https://www.loom.com/share/06f0b35f68aa40cfa21440fa12458908
## Tools Used

- Windows Server
- Active Directory Domain Services (AD DS)
- UTM
- Role-Based Access Control (RBAC)
- GitHub

## Project Timeline

- **Day 1:** Domain creation and domain controller promotion
- **Day 2:** Organizational unit and security group design
- **Day 3:** User provisioning and RBAC implementation
- **Day 4:** Incident response and resolution (NMG-0047)
- **Day 5:** Documentation and case study packaging

## Key Accomplishments

- Built the **NMG.com** domain from scratch.
- Designed an OU structure to organize users and resources consistently.
- Established a flat RBAC approach using security groups to manage access.
```
