# 🔐 Azure Admin Lab – Entra ID User, Group, MFA & Role Management

A hands-on lab simulating daily responsibilities of an Azure Administrator using Microsoft Entra ID (Azure AD), focusing on secure identity, access management, licensing, and policy controls.

## 🎯 Objective

To demonstrate proficiency in managing users, groups, licenses, MFA, and role-based access control (RBAC) in a cloud-first enterprise environment.

---

## 🧰 Lab Environment

- **Platform:** Microsoft Azure (Free Tier)
- **Tools Used:** Azure Portal, Entra ID (Azure AD), Conditional Access, Role Management, Group-Based Licensing
- **Extras:** Microsoft 365 Developer Tenant *(optional)*

---

## 🗂️ Tasks Completed

### ✅ User & Group Management
- Created 5 individual test users with unique department roles.
- Created 3 Azure AD Security Groups:
  - IT Support
  - Remote Workers
  - All Staff
- Assigned users to appropriate groups.

### ✅ License Management
- Activated Microsoft 365 E5 developer licenses.
- Assigned licenses directly to users.
- Configured **group-based licensing** for All Staff group.

### ✅ MFA Enforcement via Conditional Access
- Enabled MFA for “Remote Workers” group.
- Created Conditional Access policy:
  - Trigger: Sign-in from untrusted locations.
  - Control: Require MFA.

### ✅ Custom Role Creation & RBAC
- Created a custom role: `Helpdesk User Manager`
  - Permissions: Manage users/groups only.
- Assigned role to IT staff user (Chris).
- Verified restricted permissions applied correctly.

### ✅ Enterprise Application Access (Bonus)
- Added a sample app (Salesforce).
- Assigned access to a group.
- Configured basic SSO settings.

---

## 📸 Screenshots

> Insert screenshots in this section:
- User creation
- Group assignment
- License assignment
- MFA conditional access policy
- Custom role setup
- App assignment (optional)

---

## 🧠 Key Skills Demonstrated

- Azure Entra ID Administration
- Group-Based Licensing
- Multi-Factor Authentication (MFA)
- Role-Based Access Control (RBAC)
- Enterprise Application Assignment
- Identity Lifecycle Management

---

## 📄 Resume Description Example

**Azure Administrator Lab – GitHub Project (2025)**  
Built a simulated enterprise lab in Azure showcasing Entra ID user/group provisioning, MFA enforcement, license management, and role-based access control. Developed and tested custom admin roles, conditional access policies, and group-based licensing using real-world admin scenarios. Documented all processes in GitHub.

---

## 🔗 Useful Links

- [Azure Free Account](https://azure.microsoft.com/free)
- [Microsoft 365 Developer Program](https://developer.microsoft.com/en-us/microsoft-365/dev-program/)
