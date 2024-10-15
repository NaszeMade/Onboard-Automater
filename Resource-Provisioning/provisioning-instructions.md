# Resource Provisioning with Azure Resource Manager

### Overview
Azure Resource Manager (ARM) allows for automated deployment of resources like Virtual Machines, storage accounts, or specific permissions as part of the onboarding process.

### Steps:
1. **Define Resource Needs**:
   - Identify which Azure resources (VMs, databases, etc.) new hires will need access to.

2. **Create ARM Templates** (Optional):
   - If you’re using templates, store them in the `arm-templates/` folder for reuse.

3. **Configure Logic App Actions**:
   - In the Logic App, use the **Azure Resource Manager Connector** to deploy resources upon new user creation.

### Example ARM Template:
```json
{
  "$schema": "https://schema.management.azure.com/schemas/2019-04-01/deploymentTemplate.json#",
  "contentVersion": "1.0.0.0",
  "resources": [
    {
      "type": "Microsoft.Compute/virtualMachines",
      "apiVersion": "2021-03-01",
      "name": "[parameters('vmName')]",
      "location": "[parameters('location')]",
      "properties": {
        "hardwareProfile": {
          "vmSize": "Standard_DS1_v2"
        }
      }
    }
  ]
}
