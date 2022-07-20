# Creating a our first program with Microsoft Azure Portal and Azure Machine Learning Studio
![VirtualNetworkLogo](img/ms-azure-ml-logo.png)


---------------------------------------------------------


## Requirements
- Microsoft Azure Account ( with funds or credits )
- Microsoft Azure Suscription
- A web browser
- Access to internet

---------------------------------------------------------

## Instructions
#### 1. Login to the [Azure Portal](https://portal.azure.com/).
#### 2. Once you're on the portal's home page, you will see something like this:
![PortalImage](img/portal-main.png)
#### 3. Inside the search bar (located at the top), look for *azure machine learning* and click on it.
![Searchbar](img/searchbar.png)
#### 4. Click on *Create*.
![CreateButton](img/create-button.png)
#### 5. First, configure the resource details: select your subscription and add it to a resource group. In my case, I am creating a new resource group.
![ResourceDetails](img/resource-details.png)
#### 6. Now you'll need to configure the workspace details, you will need to give a workspace name,select and select a region. In order to use this service you will also need a storage account, a key vault, appligation insights and a container registry (optional); by default, this resources will be created with a similar name to the workspace's name, but you can change it if you want.
![WorkspaceDetails](img/workspace-details.png)
#### 7. Click on *Review + create*.
![CreateButton](img/review-and-create.png)
#### 8. If validation passed, click on *Create*.
![Create](img/create.png)
#### 9. Deployment will begin. Please wait a couple of seconds for it to complete.
![DeploymentInProgress](img/deployment-in-progress.png)
#### 10. Once deployment is complete, click *Go to resource*.
![DeploymentComplete](img/deployment-complete.png)
#### 11. Go to [Azure Machine Learning Studio](https://ml.azure.com/home) and login with your Microsoft Account.
#### 12. Look for the workspace you just created and click *Go to workspace*.
![GoToWorkspace](img/go-to-workspace.png)
#### 13. On the right left side of the page, you will see a bunch of icons in line. Click on the one with the computer icon to get to the *Compute* section.
![Compute](img/compute.png)
#### 14. Click on *New*.
![New](img/new.png)
#### 15. You will now be creating a VM instance to work on it. Give it a name and choose the lighter configuration possible; we will just be using it for a "Hello World", there's no need to give it a lot of processing power.
![VMConfiguration](img/configure-vm.png)
#### 16. When you're done configuring it, click on *Create*.
![CreateVM](img/create-vm.png)
#### 17. Wait or your VM to create.
![CreatingInProcess](img/creating-vm.png)
#### 18. When you see the state of your VM as running, that means it's ready.
![Running](img/running.png)
#### 19. On the left bar, clcik on the notebook icon to get to the *Notebook* section.
![Notebooks](img/notebooks.png)
#### 20. Click on *Create*.
![CreateNotebook](img/create-notebook.png)
#### 21. Click on the '+' button and then *Create new file*.
![CreateNewFile](img/create-new-file.png)
#### 22. Inside the white rectangle that appears on the main page, change your notebook's name if you want and then click *Create*.
![CreateNotebook](img/notebook-config.png)
#### 23. You will now be inside a Python Notebook. In order to print a "Hello World" inside the console just type:
> print("Hello world)
![HelloWorld](img/hello-world.png)
#### 24. Run your code by tapping on the "run code" button on the left side of it.
![RunningCode](img/run-code.png)
#### Extra: you can also edit your code inside VS Code by click on the Edit in VS Code button; this will open the application on your program and, once you install a couple of extensions and login to your Microsoft account, you're ready to go.
![VSCodeButton](img/edit-in-vs-code-button.png)

![VSCodeEditing](img/edit-vscode.png)
---------------------------------------------------------


## Congratulations ! You've just made your first program in Azure Machine Learning Studio !
Don't forget to delete all of your resources! If you don't, it will be very expensive.
