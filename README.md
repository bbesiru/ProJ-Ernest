# Azure Cloud Foundation Project

## Project Overview

This project demonstrates the successful setup and configuration of a Microsoft Azure Free Tier environment. The objective was to gain hands-on experience with cloud computing fundamentals, including account creation, portal navigation, resource management, identity and access management, security configuration, and cost monitoring.

Through this project, I explored key Azure services and learned how cloud resources are organized, secured, deployed, and monitored within the Azure ecosystem.

---

# Project Objectives

* Create and configure a Microsoft Azure Free Tier account.
* Explore and navigate the Azure Portal.
* Understand Azure subscriptions and resource groups.
* Learn Identity and Access Management (IAM) concepts.
* Explore Role-Based Access Control (RBAC).
* Deploy a cloud resource in Azure.
* Configure cost monitoring and budget alerts.
* Understand the Shared Responsibility Model.
* Review security features such as Multi-Factor Authentication (MFA).

---

# Step 1: Azure Account Creation

A Microsoft Azure Free Tier account was created successfully.

The registration process included:

1. Creating or signing in with a Microsoft account.
2. Completing email verification.
3. Completing phone number verification.
4. Adding a valid payment method for identity verification.
5. Activating the Azure Free Tier subscription.

### Evidence

![Azure Subscription](screenshots/01-azure-subscription.png)

---

# Step 2: Azure Portal Navigation

After account activation, the Azure Portal was explored to become familiar with the platform.

The following areas were reviewed:

* Azure Home Dashboard
* Resource Groups
* Storage Accounts
* Virtual Machines
* Microsoft Entra ID
* Cost Management + Billing
* Search Functionality

The Azure Portal search feature was particularly useful for locating services quickly.

### Evidence

![Azure Portal Dashboard](screenshots/02-azure-portal-dashboard.png)

---

# Step 3: Resource Group Creation

A Resource Group was created to serve as a logical container for Azure resources.

### Resource Details

| Item                | Value         |
| ------------------- | ------------- |
| Resource Group Name | DevOps-ErnestTraining |
| Region              | Central India   |

The Resource Group provides centralized management and organization of resources used throughout the project.

### Evidence

![Resource Group](screenshots/03-resource-group-created.png)

---

# Step 4: Resource Deployment

To gain practical deployment experience, a Storage Account was created within the Resource Group.

### Resource Details

| Item           | Value           |
| -------------- | --------------- |
| Resource Type  | Storage Account |
| Resource Group | DevOps-ErnestTraining |
| Region         | Central India     |

The deployment process demonstrated Azure's resource provisioning workflow and validation mechanisms.

### Evidence

![Storage Account Deployment](screenshots/04-storage-account-deployed.png)

---

# Step 5: Cost Management and Billing

Azure Cost Management tools were explored to understand how organizations monitor and control cloud spending.

The following areas were reviewed:

* Cost Analysis
* Budgets
* Spending Trends
* Alerts and Notifications

### Cost Management Dashboard

![Cost Management Dashboard](screenshots/05-cost-management-dashboard.png)

---

# Step 6: Budget Configuration

A budget was created to help monitor Azure spending and prevent exceeding Free Tier limits.

### Budget Configuration Process

1. Open Cost Management + Billing.
2. Select Budgets.
3. Create a new budget.
4. Define the budget amount.
5. Set the budget period.
6. Configure notification thresholds.

### Evidence

![Budget Created](screenshots/06-budget-created.png)

---

# Step 7: 64% Budget Alert Configuration

A spending alert threshold was configured at 64% of the allocated budget.

This alert ensures that notifications are sent before the budget limit is reached, allowing corrective action to be taken early.

### Example

* Budget Amount: $4
* Alert Threshold: 64%
* Notification Trigger: $2.5 Usage

### Evidence

![Budget Alert](screenshots/07-budget-alert-64-percent.png)

---

# Step 8: Microsoft Entra ID (Azure Active Directory)

Microsoft Entra ID was explored to understand identity and access management within Azure.

Areas reviewed include:

* User Management
* Authentication Methods
* Access Control
* Security Features

### Evidence

![Microsoft Entra ID](screenshots/08-microsoft-entra-id.png)

---

# Step 9: Multi-Factor Authentication (MFA)

Multi-Factor Authentication (MFA) provides an additional layer of security by requiring users to verify their identity using more than one authentication method.

### Benefits of MFA

* Reduces unauthorized access.
* Protects against stolen passwords.
* Enhances account security.
* Supports Azure security best practices.

### Steps to Enable MFA

1. Open Microsoft Entra ID.
2. Select Users.
3. Choose a user account.
4. Navigate to Authentication Methods.
5. Configure Microsoft Authenticator or another verification method.
6. Enable MFA.

### Evidence

![MFA Configuration](screenshots/09-mfa-configuration.png)

---

# Step 10: Role-Based Access Control (RBAC)

Azure Role-Based Access Control (RBAC) enables administrators to assign permissions based on user responsibilities.

### Common Roles

| Role        | Description                                  |
| ----------- | -------------------------------------------- |
| Owner       | Full access to resources                     |
| Contributor | Can manage resources but cannot assign roles |
| Reader      | View-only access                             |

RBAC follows the principle of least privilege by ensuring users receive only the permissions necessary for their tasks.

### Evidence

![RBAC Overview](screenshots/10-rbac-overview.png)

---

# Step 11: Region Selection

### Selected Region

**Central India**

### Reason for Selection

Central India was selected because it is geographically close to the deployment location, resulting in:

* Lower network latency
* Improved application performance
* Faster resource access
* Better user experience

### Evidence

![West Europe Region](screenshots/11-Central-india-region.png)

---

# Shared Responsibility Model

The Shared Responsibility Model defines how security responsibilities are divided between Microsoft Azure and the customer.

## Microsoft Azure Responsibilities

* Physical security of data centers
* Network infrastructure
* Hardware maintenance
* Platform security
* Service availability

## Customer Responsibilities

* Identity management
* Password security
* Resource configuration
* Data protection
* Access management
* Compliance and monitoring

### Application to the Deployed Storage Account

For the deployed Storage Account, Microsoft Azure is responsible for securing the underlying cloud infrastructure, including hardware, networking, and physical facilities. As the customer, I am responsible for managing user access, configuring security settings, and protecting the data stored within the Storage Account.

---

# Key Learning Outcomes

Through this project, I gained practical experience in:

* Azure account creation and management
* Azure Portal navigation
* Resource Group management
* Storage Account deployment
* Cost monitoring and budgeting
* Microsoft Entra ID administration
* Multi-Factor Authentication (MFA)
* Role-Based Access Control (RBAC)
* Cloud security principles
* Shared Responsibility Model

---

# Repository Structure

```text
ProJ-Ernest/
│
├── README.md
├── Azure_Cloud_Foundation_Project_Report.pdf
│
└── screenshots/
    ├── 01-azure-subscription.png
    ├── 02-azure-portal-dashboard.png
    ├── 03-resource-group-created.png
    ├── 04-storage-account-deployed.png
    ├── 05-cost-management-dashboard.png
    ├── 06-budget-created.png
    ├── 07-budget-alert-64-percent.png
    ├── 08-microsoft-entra-id.png
    ├── 09-mfa-configuration.png
    ├── 10-rbac-overview.png
    └── 11-cenral-india-region.png
```

# Conclusion

This project provided hands-on experience with Microsoft Azure cloud services and strengthened my understanding of cloud computing concepts, governance, security, cost management, and resource deployment. The experience established a strong foundation for further learning in Cloud Engineering and DevOps practices.
