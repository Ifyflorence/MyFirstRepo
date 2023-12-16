# How To Create And Deploy A Virtual Maching In Azure   
![image](https://github.com/Ifyflorence/MyFirstRepo/assets/99063459/ca62baff-e5ba-476a-9950-5768734d3d44)
## Step 1: Sign in to Azure Portal
- Open your web browser and go to the [Azure Portal](https://portal.azure.com/).  
- Sign in with your Azure account.
## Step 2: Navigate to the Virtual Machines service  
- In the Azure Portal, click on "Create a resource" on the left-hand side.
- In the search bar, type "Virtual machine" and select "Virtual machines" from the results.
## Step 3: Create a new virtual machine  
- Click the "+ Add" button to create a new virtual machine.
- Fill in the required information on the Basics tab:
- **Subscription**: Choose your Azure subscription.
- **Resource group**: Create a new one or select an existing resource group.
- **Virtual machine name**: Enter a unique name for your VM.
- **Region**: Choose the Azure region for your VM.
- **Image**: Select an operating system image (e.g., Windows, Linux).
- **Size**: Choose the size of the VM based on your requirements.
- **Authentication type**: Choose how you want to connect to the VM (SSH key or password for Linux, password for Windows).
- **Username/Password or SSH public key**: Provide the necessary credentials.
- Click "Next" to proceed to the Disks tab. Configure the disk settings according to your needs.
- Click "Next" to move to the Networking tab. Configure network settings, such as Virtual Network, Subnet, Public IP, and Network Security Group.
- Click "Next" to go to the Management tab. Set any optional configurations, such as Boot diagnostics, Auto-shutdown, etc.
- Click "Review + create" to review your settings. If everything looks good, click "Create."
- Azure will validate your configuration. Once validation passes, click "Create" to deploy the virtual machine.
## Step 4: Monitor deployment progress  
- You'll be redirected to the deployment overview page. Monitor the deployment progress. This may take a few minutes.
## Step 5: Connect to your virtual machine  
- Once the deployment is complete, go back to the Azure Portal.
- Navigate to the "Virtual machines" section and select your newly created VM.
- Click on the "Connect" button.
## Step 6: Connect using Remote Desktop Protocol (RDP) or SSH  
- For Windows VMs: Use Remote Desktop Protocol (RDP) with the provided credentials.
- For Linux VMs: Use SSH with the provided credentials.
## Step 7: Cleanup (Optional)  
- If you're done with the VM, you can delete it to stop incurring charges. Go to the VM resource in the Azure Portal, click "Delete," and confirm.
### Congratulations! You've successfully created and deployed a virtual machine in Azure.
