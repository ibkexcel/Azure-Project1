                                     #Azure-Project1
								
                                **Azure Project Description**
Azure Project Setup - Personal Documentation A comprehensive documentation of my Azure cloud journey, covering account setup, resource management, cost optimization, and security implementation.

                                Project Highlights
                                Account & Access Setup
Successfully created and configured Azure account with multi-step verification (email, phone, credit card). Mastered Azure Portal navigation including portal menu customization, breadcrumb navigation, global search functionality, and created a personalized dashboard for efficient resource monitoring.

                                  Resource Organization
Created the 3MTT-PROJECT resource group in the US West region with successful provisioning. Applied the Shared Responsibility Model understanding, clearly defining the division of security and management responsibilities between Microsoft (infrastructure, network, hypervisor) and customer (applications, data, endpoints).

                                  Cost Management Configuration
Implemented comprehensive cost tracking through Azure Cost Management tools. Configured cost analysis with custom filter parameters, established budget alerts at 75% threshold ($150), and set up email notifications for spending anomalies. Documented Free Tier limits including Azure App Service quotas and Cosmos DB account limits (1000 RU/s, 25 GB storage).

                                  Security Implementation
Enforced enterprise-grade security controls including Multi-Factor Authentication (MFA) for all users, strong password policies for cloud and hybrid accounts, and Conditional Access policies for risk-based authentication. Integrated Microsoft Authenticator and prepared for password-less authentication methods (Windows Hello, FIDO2 security keys).

                                    Storage & Services
Deployed Azure Storage Account with unique namespace for blob, file, queue, and table storage. Configured for durability, high availability, security, and massive scalability with appropriate redundancy options for global HTTP/HTTPS access.

                                    Ongoing Monitoring
Established continuous monitoring framework for regular cost analysis reviews, budget alert management, security recommendation reviews, and Free Tier resource optimization to maintain cost-effective and secure cloud operations. Purpose This repository serves as personal documentation of my Azure learning journey and practical implementation of cloud infrastructure best practices.						  
							
                                  Additional Details
Specific Azure services used (App Service, Cosmos DB, Storage Account specs) Configuration values and thresholds you set Screenshots or architecture diagrams references Challenges faced and solutions implemented Extra Sections to Add:

                                  Prerequisites 
What you needed before starting (email, payment method, etc.) Next Steps - Future Azure services you plan to explore Lessons Learned - Key takeaways from the setup process Resources - Links to Azure documentation you found helpful Tech Stack - Specific Azure services and tools used Getting Started - How others can replicate your setup Project Structure - Overview of your repository organization.

                                 Completion Checklist
Contains full completion checklisting of Account Creation, Navigation & Access set-up.	

                                 Troubleshooting Checklist/Support
The Troubleshooting checklist shortly highlights a number of pathway solutions to addressing various issues. While the Microsoft premier support option highlights the Professional assistance services Microsoft offers in addressing issues effectively.

							 
                                       **PROJECT CONTENT**
                           Azure Portal Dashboard Screenshot
<img width="988" height="557" alt="image" src="https://github.com/user-attachments/assets/de5b9556-1711-4587-982b-8903d453a06c" />
Account Creation Documentation:
To create an Azure account with my email, phone, and credit card verification, I followed these steps:
Sign Up for Azure:
I navigated to the Azure sign-up page - https://signup.azure.com/.
I Clicked on "Try Azure for Free" to begin the sign-up process.
Provide Personal Information:
I entered information on country/region, first name, last name, email address, and phone number in the input fields inside the Personal info dialog box.
Verify Identity by Phone:
I chose to either receive a verification code via SMS or phone call.
Subsequently, I entered the code received to verify my phone number.
Verify Identity by Credit Card:
I entered my credit card information for identity verification.
Agree to Terms:
I reviewed the terms and conditions.
I checked the box to accept the terms and clicked "Sign up" to finish up.
Complete Account Creation:
Once all my information was verified, my Azure account was created.
Finally, I was redirected to the Azure portal dashboard.

                                         Azure Portal Navigation:
Navigating the Azure Portal
 To effectively navigate the Azure portal, it's important to understand its key elements and how to access various    services. Here's a step-by-step guide:
Portal Menu:
The portal menu is my primary navigation tool. It allows me to quickly access key functionalities and resource types. It’s found on the left side of the Azure portal.
I can choose between fly-out mode (hidden until needed) or docked mode (always visible) for the portal menu.
Breadcrumbs:
Breadcrumbs are located at the top of the page and help’s to track one’s navigation path. They allow me to move back a level in my workflow easily.
Global Search:
I use the search bar in the page header to quickly find specific resources, services, or documentation.
Dashboard:
The dashboard provides a focused view of the resources in my subscription. I can customize it to display frequently used resources or other important information.
Accessing Key Services:
Compute Services: To access compute services like Virtual Machines, I navigate to the portal menu and select "Compute" or use the search bar to find specific services.
Storage Services: For storage services, I select "Storage" from the portal menu or search for specific storage accounts or services.
Service Menu:
When I select a specific service or resource, a service menu will appear with commands specific to that area. This menu helps me manage and configure the selected service.

                                     Custom Dashboard Screenshot
        <img width="1073" height="605" alt="image" src="https://github.com/user-attachments/assets/6640264f-7412-4f5b-8239-b064287033e7" />
Process Undertaken to Create a Custom Dashboard:
To create a custom dashboard for my Azure subscription, I followed these steps:
Sign in to the Azure Portal:
I navigated to the Azure portal and signed in with my credentials.
Access the Dashboard:
From the Azure portal menu, I selected Dashboard. This took me to the default dashboard view.
Create a New Dashboard:
I clicked on Create and then select Custom. This opened the Tile Gallery and an empty grid representing the dashboard layout.
Name Your Dashboard:
Click on the text in the dashboard label to enter a name that helps you easily identify your custom dashboard.
Add Tiles:
I used the Tile Gallery to select and add tiles that display different types of information relevant to my needs. I arranged these tiles on the grid to customize the layout.
Save the Dashboard:
Once I had arranged my tiles, I clicked Save in the page header to save my custom dashboard.
Access and Manage Dashboards:
I could now view my new dashboard by selecting the arrow next to the dashboard name to see other available dashboards. This list may include dashboards shared by other users.

                                         3MTT-PROJECT Resource Group
            <img width="1073" height="605" alt="image" src="https://github.com/user-attachments/assets/fbdb5866-127a-4ecf-bc1e-b18d88c73e07" />
The Resource Group named "3MTT-PROJECT" was successfully created and is in the "Succeeded" provisioning state. This indicates that the Resource Group is fully operational and ready for use in your Azure portal directory.
Summary Report.  
Region Selection
•	Region: US West
The US West region is known for its robust infrastructure and connectivity, making it a popular choice for deploying Azure resources. It offers high availability and scalability options to support various workloads.
Shared Responsibility Model
•	Overview:
•	The Shared Responsibility Model in Azure defines the division of responsibilities between Microsoft and the customer. It varies based on the type of service model used: Infrastructure as a Service (IaaS), Platform as a Service (PaaS), or Software as a Service (SaaS).

•	Responsibilities:
	Microsoft's Responsibilities:
Microsoft is responsible for the security and reliability of the Azure platform, including the physical infrastructure, network, and hypervisor layer.
Microsoft provides built-in features and services to enhance reliability, such as availability zones and backup strategies.
    Customer's Responsibilities:
Customers are responsible for securing their applications, data, and endpoints.
Customers must configure and manage their resources, including maintaining the operating system and application layers in IaaS, and ensuring application reliability in PaaS and SaaS models.
•	Application Example:
When deploying resources in Azure, customers must ensure their applications are optimized for performance and security. This includes configuring firewall settings, monitoring network traffic, and managing data access.
This report provides a concise overview of the region chosen for your resources and how the Shared Responsibility Model applies to your Azure deployment.

                         Getting Started Screenshot(Cost Management Section)
       <img width="1073" height="605" alt="image" src="https://github.com/user-attachments/assets/3b2557d7-66de-470c-b8ae-c267b94c81a5" />
                  **Page (Getting Started) Highlights:**
Getting Started Column is an overview display page to manage billing for products and services in my billing account.  It has a list of icons to configure access usage, creating budgets, view billing profiles and send transfer requests on full display.

                        Summary Section Screenshot
      <img width="1073" height="605" alt="image" src="https://github.com/user-attachments/assets/df73bbb4-f8bd-420c-b025-9796f6970720" />
      Page (Summary Section) Highlights:
This page is an overview display page to view the summary for outstanding payment billing invoices, upcoming invoices, invoices accumulation over time period, spending rate and forecast, monthly product by charges, billing alerts, shortcuts and remaining credit alerts.

                        Cost Analysis Screenshot
      <img width="1073" height="605" alt="image" src="https://github.com/user-attachments/assets/00bc04c2-8ea6-4d60-b8e6-0bd1f9705051" />
               **Page (Cost Analysis) Highlights:**
The Cost analysis display page under the Cost management section is the configuration setup page for my billing account. It displays three sections by default with each having a number of filter item type parameters selection drop-down options to select for a resource or service type category.
                       Cost Alert Screenshot
       <img width="1073" height="605" alt="image" src="https://github.com/user-attachments/assets/c69b27ce-d5dd-4eec-ad13-15888f70149a" />
     Page (Cost Alert) Highlights:
The display page is where I get to configure to subscribe for alerts, get notified about changes, and add new alert rules for Users.

                       Budget Alert Screenshot
      <img width="1073" height="605" alt="image" src="https://github.com/user-attachments/assets/78a0493b-7e91-4032-b5e8-81b8c19e47f4" />
Page (Budget Alert) Highlights:
The budget alert display page under Cost Management allows me to set and manage budget thresholds and alerts for my Azure spending. It provides a visual overview of my budget status, including notifications when spending reaches certain thresholds, such as 75%, helping me monitor and control costs effectively. From the page screenshot displayed, alert conditions set for budget alerts shows forecasted cost type selection made along with the calculated total estimated 75% budget for time period valued at $150. Any futuristic alert notifications get forwarded to my email which was added for same purpose.

                               Free Tier Limits and Summary
Here are the resource quotas for the Azure Free Tier:
Azure App Service Free Plan Quotas:
CPU (Short): Limited CPU usage in a five-minute interval, resetting every five minutes.
CPU (Day): Total CPU usage allowed per day, resetting every 24 hours at midnight UTC.
Memory: Total memory usage allowed.
Bandwidth: Total outgoing bandwidth allowed per day, resetting every 24 hours at midnight UTC.
Filesystem: Total storage allowed.
Azure Cosmos DB Free Tier Account Limits:
Number of Free Tier Accounts per Azure Subscription: 1
Duration of Free-Tier Discount: Lifetime of the account.
Maximum RU/s for Free: 1000 RU/s
Maximum Storage for Free: 25 GB
Maximum Number of Containers in a Shared Throughput Database: 25
These quotas are designed to help me get started with Azure services, develop, test applications, or run small production workloads for free.

                             Security Considerations
Here are the security settings, password policies, and MFA preparation for my Azure subscription:
Strong Authentication Controls:
Enforce multi-factor authentication (MFA) for all users, select users, or at the per-user level based on sign-in conditions and risk factors.
Use password-less authentication methods such as Windows Hello for Business, Microsoft Authenticator app phone sign-in, and FIDO2 security keys.
Password Policies:
Cloud-only accounts have a default baseline password policy.
Hybrid accounts follow on-premises password policies.
For third-party applications and services, disable or change default IDs and passwords during initial service setup.
MFA Preparation:
Enable Azure MFA and follow Microsoft Defender for Cloud identity and access management recommendations.
Use Conditional Access policies for advanced scenarios to enforce MFA only in specific situations, such as sign-ins from unfamiliar locations.
These measures help protect an organization from compromised credentials and unauthorized access, ensuring a secure environment for your Azure subscription.

                        Cost Management overview section.
		<img width="1073" height="605" alt="image" src="https://github.com/user-attachments/assets/f77ac9bc-1521-4971-85fa-73ae36c80606" />
                          Cost Analysis and Budgets in Azure
Cost Analysis is a tool within Azure that helps you visualize and analyze your organizational costs. It allows you to:
Understand what you're spending and where you're spending it.
View aggregated costs by organization to identify spending trends.
Estimate monthly, quarterly, or yearly cost trends against a budget.
Create budgets to adhere to financial constraints and monitor daily or monthly costs.
Budgets in Azure enable you to manage costs by setting spending limits and creating alerts for spending anomalies or overspending. You can create budgets as early as when you create a subscription to ensure you stay on top of your costs from the start.
These tools are available from every resource group; subscription, management group, and billing account in the Azure portal, providing a comprehensive view of your costs and helping you manage your cloud investment effectively.

				      Storage Account Screenshot
<img width="1073" height="605" alt="image" src="https://github.com/user-attachments/assets/e82b7b3e-ec92-4bb7-9166-eb11b54ee9eb" />
A Storage account on Azure is a service that provides a unique namespace for storing your Azure Storage data objects, such as blobs, files, queues, and tables. It allows me to access my data from anywhere in the world over HTTP or HTTPS. Azure Storage accounts are designed to be durable, highly available, secure, and massively scalable, making them suitable for a wide range of applications and workloads. They support different types of storage services and redundancy options, ensuring that my data is protected and accessible when needed.

                     Azure Project Setup Completion Checklist:
Account & Access Setup
✅   Create Azure account with email, phone, and credit card verification
✅   Navigate and familiarize yourself with Azure Portal layout
✅   Configure portal menu (fly-out or docked mode)
✅   Set up global search and breadcrumb navigation
✅   Create custom dashboard for resource monitoring
Resource Organization
✅   Create Resource Group (e.g., "3MTT-PROJECT")
✅   Select appropriate region (e.g., US West)
✅   Verify Resource Group provisioning status is "Succeeded"
Cost Management Configuration
✅   Access Cost Management section
✅   Review billing account overview and payment methods
✅   Set up Cost Analysis with filter parameters
✅  Create budget thresholds (e.g., 75% alert at $150)
✅   Configure cost alerts and email notifications
✅   Review Free Tier limits and quotas
✅   Monitor spending rate and forecast trends
Security Implementation
✅   Enforce Multi-Factor Authentication (MFA) for users
✅   Configure strong password policies
✅   Set up Conditional Access policies
✅   Enable Azure MFA with Microsoft Authenticator
✅   Review Microsoft Defender for Cloud recommendations
✅   Change default credentials for third-party services
Storage & Services
✅   Create Storage Account with appropriate redundancy
✅   Configure blob, file, queue, or table storage as needed
✅   Set up access controls and security for storage
Ongoing Monitoring
☐ Regular cost analysis reviews (weekly/monthly)
☐ Monitor budget alerts and adjust as needed
☐ Review security recommendations
☐ Optimize resource usage within Free Tier limits

                   Troubleshooting Checklist
Route All: Ensure that all traffic is routed correctly.
NAT Gateway: Associate an Azure Network Address Translation (NAT) Gateway for predictable outbound IPs.
Network Security: Verify network security groups (NSG) and user-defined routes (UDR) rules.
App Settings: Check for any missing app settings in the logic app runtime configuration.
Private Storage Accounts: Deploy single-tenant logic apps with private storage accounts and ensure configurations align with deployment requirements.
DNS and Host Settings: Verify DNS and host settings for proper connectivity.
Support Resources
Self-help Troubleshooting: Access self-help content for resolving system issues. Refer to Service Fabric troubleshooting guides.
Azure Support Request: Open a support ticket on the Azure portal for issues related to your Service Fabric cluster.

                 Microsoft Premier Support 
Consider Microsoft premier support for professional assistance.
These steps and resources can help ensure that one’s Azure project is well-supported and any issues are effectively addressed.

				  


