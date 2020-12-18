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

## STEP 3

### Download the exercise files
The files used in this module (and other related modules) are published in a GitHub repository, which you need to clone to your Python environment. If you haven't already cloned the ai-fundamentals repository in a previous module, use the following steps to clone it to your Azure Machine Learning workspace:

1. In Azure Machine Learning studio , view the Notebooks page (under Author). This page contains a notebook editor that you can use to run notebooks.

2. Under My files, use the 🗋 button to create a new file with the following settings:

      - **File location:** Users/your user name
      - **File name:** Get-Files
      - **File type:** Notebook
      - **Overwrite if already exists:** Selected
3. When the new notebook has been created, ensure that the compute instance you created previously is selected in the Compute box, and that it has a status of Running. Then, in the rectangular cell that has been created in the notebook, paste the following code:

```
!git clone https://github.com/MicrosoftDocs/ai-fundamentals
```
4. Use the ▷ button next to the cell to run the code it contains. This will clone the exercise files from GitHub.

5. When the code has finished running and the checkout of the file is done, use the ↻ button under My files to refresh the folder view, and verify that a folder named ai-fundamentals has been created. This folder contains notebooks and other files used in the exercise.

6. Close the Get-Files.ipynb notebook tab.

## STEP 4

### Try & Complete 

After you have set up the Python environment and cloned the ai-fundamentals repository, you're ready to experiment with creating a bot.

1. Open the QnA Bot.ipynb notebook in the ai-fundamentals folder. If you're using the notebook editor in Azure Machine Learning studio, use the ≪ button to collapse the file explorer pane and give you more room to focus on the notebook tab.
2. Read the information in the notebook, and run the code cells it contains in order.

## STEP 5

### Cleaning-up

If you used a compute instance in Azure Machine Learning studio, you should stop it to avoid using Azure credits unnecessarily.

1. In Azure Machine Learning studio, view the Compute page (under Manage).
2. On the Compute Instances tab, select your compute instance and then use the Stop button to stop it.

### Happy Coding !! 

***Credits Goes to Microsoft - [Reference](https://docs.microsoft.com/en-us/learn/modules/build-faq-chatbot-qna-maker-azure-bot-service/3-create-bot)***


