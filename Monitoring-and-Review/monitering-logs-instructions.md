# Monitoring and Logs for Workflow Success

### Overview
Ensuring the onboarding workflow runs smoothly is critical to the success of this project. Monitoring Azure Logic Apps and Azure AD logs helps identify any issues early.

### Monitoring the Logic App:
1. **View Runs History**:
   - In the Azure portal, navigate to your Logic App and check the **Runs History** tab to track each execution of the workflow.

2. **Set Up Alerts**:
   - Configure alerts through Azure Monitor to notify you if a run fails or if there are issues with user creation or resource provisioning.

### Monitoring Azure AD Logs:
1. **Azure AD Activity Logs**:
   - Use the **Azure AD Logs** to track user creation, role assignments, and other actions to ensure compliance.

2. **Auditing and Compliance**:
   - Set up **auditing policies** in Azure AD to keep track of who has access to which resources and roles.
