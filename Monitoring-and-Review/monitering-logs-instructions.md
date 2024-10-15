# Onboard Automator: Monitoring and Logs Setup Guide

### Overview
As part of the **Onboard Automator** project, I implemented comprehensive monitoring and alerting strategies to ensure seamless automation of employee onboarding processes in Azure. This guide outlines the setup for monitoring Logic Apps and Azure AD logs, enabling proactive identification and resolution of potential issues.

### Steps to Set Up Monitoring and Alerts
1. **Access Azure Monitor**
   - In the **Azure Portal**, navigate to **Monitor** from the left-hand sidebar to manage alerts and monitoring settings effectively.

2. **Create a New Alert Rule**
   - Click on **New Alert Rule** to initiate the alert setup.
   - Select the Logic App associated with the **Onboard Automator** as the target resource.

3. **Define Alert Condition**
   - Under the **Conditions** section, click on **Add Condition**.
   - Choose the appropriate metric (ex: “Run Failed”) to trigger alerts when a workflow execution encounters issues.

4. **Configure Notifications**
   - In the **Actions** section, establish an **Action Group** to define notification recipients.
   - Select preferred notification methods (ex: email, SMS) to ensure timely updates on alert conditions.

5. **Review and Create**
   - After configuring the alert parameters, review the settings for accuracy and click **Create** to finalize the alert rule.

### Monitoring Logic App Runs History
1. **Navigate to Logic Apps**
   - In the **Azure Portal**, select **Logic Apps**, then choose the relevant Logic App for the **Onboard Automator** project.

2. **Check Runs History**
   - From the left panel, select **Runs History** to review the status of all workflow executions, whether successful or failed.

3. **Review Individual Runs**
   - Click on a specific run to access detailed logs and error messages for each action within the workflow. This facilitates immediate troubleshooting and insights.

### Reviewing Azure Entra ID Logs for Onboarding
1. **Go to Azure Entra ID Directory**
   - In the **Azure Portal**, access **Azure Entra ID Directory** > **Sign-ins** to monitor user activities.

2. **Audit Sign-ins and Activities**
   - View logs for all users, including newly onboarded employees, to verify correct resource assignments and compliance with governance policies.

### Conclusion
Implementing robust monitoring and alerting for the **Onboard Automator** project enhances operational reliability and efficiency. Regular checks of runs history and alerts empower timely responses to potential issues, ensuring a smooth onboarding experience for new employees.
