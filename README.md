# SampleGitHubActions
A simple .Net applcation deployed on Azure App Service at [.website](https://githubactionssamplehtml.azurewebsites.net/)
for the purpose of showcasing GitHub actions at work to ADNEC during the enablement Session. 
# Course of action
1. The website is a simple .Net core application hosted in a GitHub repository on the Liveroute account
2. A second account, personnal github account was added as contributor to this project.
3. Using the personal Github account changes were made to the local directory and then pushed to GitHub
4. GitHub actions took care of building the project with the new changes included and then deploying it to Azure Web Apps

# Setting up 
### 1. Azure Web App 🪐
In the Azure portal a Web app was created using chosen configuration of:<br />
1.  **Subscription and Resource Group**
2.  **Web App name** : *GitHubActionsSampleHTML*
3.  **Publish method** : _Code_
4.  **Runtime stack** : _.NET 6_
5.  **Region** : *UAE North*
6.  **Operating System** : _Windows_
8.  **App service plan (also called pricing plan)** 

Afterwards click **Review + create**

#### After finsihing the bellow step _GitHub actions_ part come back here:
Go the ressource and choose **Deployment Center**:
From there in **Settings** you can manage the **Source** section
Sign in to your GitHub account and select the repository you wish to have as your source code.

 
### 2. GitHub Actions.
On the GitHub website when accessing your repository, notice the action tab
from there select **deploy new workflow**  and then **Set up your own workflow**
This were you will create your YAML file for deployment.
