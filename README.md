# Intelligent-Bots-in-Azure

## STEP 1
  
### Create an Azure Machine Learning workspace
If you already have an Azure Machine Learning workspace in your Azure subscription, in a new browser tab, navigate to Azure Machine Learning studio  and sign into Azure Machine Learning studio using your Microsoft account. Otherwise, follow these steps to create a new workspace:

1. Sign into the Azure portal  using the Microsoft account associated with your Azure subscription.
2. Select ＋Create a resource, search for Machine Learning, and create a new Machine Learning resource with the following settings:
- **Workspace Name:** enter a unique name of your choice
- **Subscription:** your Azure subscription
- **Resource group:** create a new resource group with a unique name
- **Location:** choose any available location
3. Wait for your workspace resource to be created (it can take a few minutes). Then go to it in the portal, and on the Overview page for your workspace, launch Azure Machine Learning studio (or open a new browser tab and navigate to https://ml.azure.com ), and sign into Azure Machine Learning studio using your Microsoft account.
4. In Azure Machine Learning studio, toggle the ☰ icon at the top left to view the various pages in the interface. You can use these pages to manage the resources in your workspace.

## STEP 2

### Create a compute instance
To run the notebook used in this exercise, you will need a compute instance in your Azure Machine Learning workspace. If you already have one, start it; otherwise, follow these instructions to create one:

1. In Azure Machine Learning studio  , view the Compute page (under Manage).
2. On the Compute Instances tab, create a new compute instance with the following settings:
- **Region:** choose any available location
- **Virtual** Machine type: CPU
- **Virtual Machine size:** Standard_DS11_v2
- **Compute name:** enter a unique name
3. Wait for the compute instance to start (this may take a minute or so)


