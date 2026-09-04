# Active Directory Domain Services — Administration Lab

## 📌 Project Overview

A hands-on Active Directory Domain Services (AD DS) laboratory environment designed to simulate the administration of a small-to-medium business network.

The project focuses on building a structured Active Directory environment, organizing users through Organizational Units (OUs), and performing common user account administration tasks using Windows Server.

---

## 🖥️ Lab Environment

- **Operating System:** Windows Server
- **Directory Service:** Active Directory Domain Services (AD DS)
- **Domain:** `IsaacA.local`
- **Virtualization Platform:** VMware
- **Management Tool:** Active Directory Users and Computers (ADUC)
- **Environment Type:** Virtualized laboratory / enterprise IT simulation

---

## 🏢 Active Directory Structure

The domain was organized using a departmental OU hierarchy designed to represent a realistic business environment.

### Main Organizational Units

The environment contains **8 main departmental OUs**:

- IT Department
- HR Department
- Finance Department
- Sales Department
- Management
- Customer Support
- Marketing
- Operations

### Child Organizational Units

Child and nested OUs were created beneath the departmental OUs to separate different types of Active Directory objects, including:

- Users
- Computers
- Groups
- Service Accounts

This structure provides a foundation for future Group Policy management, permissions, and administrative delegation.

---

## 👥 User Administration

A total of **40 domain user accounts** were created across the organization's departments.

User accounts were configured with:

- Unique usernames
- Department-specific organization
- Job titles
- Initial passwords
- Password-change requirements at first logon
- Appropriate account options
- Verified user properties

Users were organized into their corresponding departmental User OUs.

---

## 🛠️ Skills Practiced

### Organizational Unit Management
- Created top-level departmental OUs
- Created child and nested OUs
- Designed a hierarchical AD structure
- Organized objects according to department

### User Account Management
- Created domain user accounts
- Configured usernames
- Assigned job titles
- Configured initial passwords
- Configured first-logon password requirements
- Verified user account properties
- Modified user information

### Account Administration
- Enabled and disabled user accounts
- Practiced password reset procedures
- Reviewed account options
- Performed basic account troubleshooting

---

## 🔐 Security Considerations

This laboratory environment was created for educational and practical training purposes.

No real organizational credentials or sensitive production information are used.

Passwords used during the laboratory exercises are temporary training credentials and should not be reused in production environments.

---

## 🎯 Learning Objectives

The primary objectives of this laboratory are to develop practical experience with:

1. Active Directory Domain Services
2. Organizational Unit design
3. Domain user administration
4. Account configuration
5. Basic Active Directory troubleshooting
6. Enterprise-style directory organization

---

## 📈 Future Lab Development

Future stages of the laboratory will expand the environment to include:

- Computer account management
- Domain-joined Windows clients
- Security group management
- Group Policy
- File and folder permissions
- Account lockout troubleshooting
- Help Desk troubleshooting scenarios
- ServiceNow incident documentation
- Additional Active Directory administration tasks

---

## 👨‍💻 Project Status

**Status:** Active / In Progress

This repository documents the development of a hands-on Active Directory laboratory environment and will be updated as additional administration and troubleshooting skills are practiced.
