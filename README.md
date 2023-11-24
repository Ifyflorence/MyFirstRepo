# How To Create And Deploy A Virtual Maching In Azure 
## Step 1: Sign in to Azure Portal
- Open your web browser and go to the [Azure Portal](https://portal.azure.com/).  \
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
