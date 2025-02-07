<h1>🔑 User Authentication & Access Control Lab</h1>

<h2>📌 Overview</h2>
This project demonstrates **user authentication and access control** implementation using **Active Directory (AD), NTFS permissions, and TrueNAS ACLs**. The lab covers **security group management, folder access restrictions, and SMB share configurations** to enforce access policies.

<h2>🛠 Tools & Technologies Used</h2>

- **Active Directory (ADUC)** – User/group management  
- **NTFS Permissions** – Folder-level access control  
- **TrueNAS ACLs** – Permission enforcement for shared storage  
- **Windows Server** – Authentication & domain management  

<h2>🔍 Key Findings & Implementation</h2>

| Security Feature | Description | Implementation |
|-----------------|-------------|----------------|
| **Active Directory Security Groups** | Centralized user management via group-based access control. | Created **HR, MGR, and DEV** security groups and assigned users accordingly. |
| **NTFS Folder Permissions** | Enforced access control at the filesystem level. | Configured **HRfiles, MGRfiles, and DEVfiles** with role-based access. |
| **SMB Shares & TrueNAS ACLs** | Controlled file access over a network. | Set up **restricted network shares** with granular ACL settings. |
| **Authentication Verification** | Ensured users only accessed authorized resources. | Tested **successful and denied access** scenarios for each user. |

<h2>🚀 Report & Documentation</h2>

📄 **[Download Full Report (PDF)](https://github.com/user-attachments/files/18664963/Applying.User.Authentication.and.Access.Controls.4e.-.Marc.Corona.pdf)**  

📂 **Screenshots & Configuration Files**:
- `ad_users_groups.png` – ADUC users and groups  
- `ntfs_hrfiles_permissions.png` – NTFS security settings for HRfiles  
- `smb_share_config.png` – TrueNAS ACL settings for shared folders  

<h2>✅ Key Takeaways & Security Best Practices</h2>

🔹 **Role-Based Access Control (RBAC)** ensures **least privilege access** for users.  
🔹 **NTFS & ACL permissions** should be **tightly controlled** to prevent unauthorized access.  
🔹 **Authentication logs** help detect **unauthorized access attempts** and misconfigurations.  

---
