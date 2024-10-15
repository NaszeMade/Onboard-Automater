# Onboard Automator: Logic App Runs History and Monitoring Guide

### Overview
In my **Onboard Automator** project, I established a systematic approach to monitoring Logic App workflows to ensure successful automation of employee onboarding. This guide details how to access and analyze the Runs History, troubleshoot errors, and maintain operational efficiency.

### Steps to View the Runs History
1. **Navigate to Your Logic App**
   - In the **Azure Portal**, select **Logic Apps** and choose the Logic App designated for the **Onboard Automator** project.

2. **Access Runs History**
   - In the left-hand navigation pane, click on **Runs History** to view all executions of your Logic App, categorized by success and failure.

   ![Runs History Tab](./runs-history-screenshot.png) 

3. **Inspect Run Details**
   - Each execution is timestamped, with statuses: **Succeeded**, **Failed**, or **Running**. 
   - Select any run to explore detailed logs and outputs for each action in the workflow, facilitating effective troubleshooting.

4. **Filter and Search**
   - Utilize filters at the top of the **Runs History** screen to find specific runs by status or date range, enhancing audit efficiency.

### Diagnosing and Troubleshooting Errors
1. **Identify Failed Runs**
   - Highlighted in red, failed runs indicate issues. Click on these runs to examine error messages and details.

2. **Examine Error Messages**
   - Azure provides descriptive error information for each step. Analyze these messages to identify root causes, such as invalid input or permissions issues.

3. **Retry Failed Runs**
   - Logic Apps permit manual retries for failed executions. From the **Runs History** tab, select a failed run and click **Resubmit** to rerun the workflow with the same input data.

### Setting Up Alerts for Workflow Failures
1. **Create Alerts**
   - In the **Azure Portal**, navigate to **Monitor** > **Alerts** > **New Alert Rule**.
   - Choose your Logic App as the resource and set conditions to trigger alerts on workflow failures.
   - Define severity levels and configure notification channels for immediate updates.

2. **Monitor Alerts**
   - Alerts ensure quick notification of workflow issues, enabling swift actions to mitigate impacts on operations.

### Logs for Compliance and Auditing

1. **Export Runs History**
   - Utilize the export feature in the **Runs History** tab for auditing and record-keeping purposes.

2. **Azure AD Logs**
   - Regularly review **Azure AD Logs** for discrepancies in user creation or role assignments, ensuring compliance with governance and security policies.

### Best Practices for Monitoring
- **Set Up Recurring Alerts**: Regular alerts help in monitoring critical workflows and ensuring responsiveness.
- **Review Runs History**: Periodic reviews of Runs History allow for identifying patterns and rectifying consistent errors.
- **Perform Manual Audits**: For sensitive environments, conduct manual audits of Logic App executions and Azure AD activities to verify compliance and correctness.

By adhering to this structured monitoring approach, it ensures that the **Onboard Automator** project operates smoothly, providing efficient onboarding for new employees while maintaining compliance and security standards.
