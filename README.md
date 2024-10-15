# Onboard Automator: Streamlined Azure AD Identity and Governance

### Overview
Onboard Automator is a no-code Azure-based solution designed to automate the onboarding process for new employees. By leveraging Azure Logic Apps, Azure AD, and Azure Resource Manager, the solution eliminates manual work, ensuring fast, accurate provisioning of resources and access for new hires.

**Project Goals**:
- Automate employee onboarding into Azure Active Directory.
- Assign roles and provision necessary resources without coding.
- Ensure secure and consistent user management through Azure’s built-in governance tools.

### Azure Services Used
- **Azure AD**: Handles identity creation and role assignment.
- **Azure Logic Apps**: Automates the workflow from user creation to resource provisioning.
- **Azure Resource Manager**: Provisions resources like virtual machines or access permissions.
- **Azure Email Service**: Sends automated emails to new employees with their credentials and instructions.

### Key Features
- **No programming required**: This project fully utilizes Azure's native services to automate processes without writing code.
- **Efficient onboarding**: Automatically triggers workflows for new hires, streamlining user creation and resource assignment.
- **Governance compliance**: Ensures proper role assignment and access control following best practices in identity management.

### Workflow Overview
1. **Trigger Event**: A trigger initiates the process, such as a new hire request via email or SharePoint.
2. **User Creation**: Logic Apps creates a new Azure AD user based on the trigger details.
3. **Role Assignment**: The user is assigned roles and groups depending on their department or position.
4. **Resource Provisioning**: Azure resources are provisioned automatically using Azure Resource Manager.
5. **Welcome Email**: A welcome email is sent to the new hire with access credentials.
6. **Monitoring**: The workflow is monitored via Logic Apps and Azure AD logs for errors and success tracking.

For detailed implementation instructions, visit the respective documentation in each folder.

### Why This Project Matters
By automating identity management and resource provisioning, this project demonstrates proficiency in Azure services and workflow automation without the need for custom code. It's a scalable solution for organizations aiming to streamline their employee onboarding process.

### Steps Overview
1. [Azure AD Setup](./Azure-AD-Setup/ad-setup-instructions.md)
2. [Logic App Workflow Design](./LogicApp-Workflow/instructions.md)
3. [User Creation in Azure AD](./LogicApp-Workflow/instructions.md)
4. [Role and Group Assignment](./LogicApp-Workflow/instructions.md)
5. [Resource Provisioning](./Resource-Provisioning/provisioning-instructions.md)
6. [Welcome Email](./LogicApp-Workflow/instructions.md)
7. [Monitoring and Review](./Monitoring-and-Review/monitoring-logs-instructions.md)

For detailed steps, refer to the respective folders and instructions.
