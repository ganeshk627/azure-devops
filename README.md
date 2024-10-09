# azure-devops

# Creating Organization Account and Projects
1. Go to dev.azure.com then click 'Get Started with Azure' then create or use existing accounts
2. Search for 'Azure Devops' then select it
3. Click "My Azure DevOps Organizations" link then create an organization by providing name
- Private Projects only available inside the Organization


# Organization Settings
- Once we created an Organization we could see an option called 'Organization Settings' at the left bottom corner. Once we click 'Organization Settings', we could see settings such as below:
1. General Settings
    - Overview:
        - Name - name of our organization along with handle URL
        - Privacy Url
        - Description
        - Timezone
        - Region
        - Organization usage limit
            - Projects (1000 max) 
            - Work Item Tags (150000 max)
        - Organization owner
            - Change owner
        - Delete Organization --> To delete organization
    - Projects: List of projects under the particular organization will be available with details
        - Able to create new project
        - Able to change visibility, process
    - Users:
        - Able to add users but not the users outside the organization
            - Readers --> Clients
            - Contributors --> Having project permissions and not userlevels such as Developers and their team
            - Adminstrators --> Complete permission
        - Able to add Group rules and modify rules
    - Billing
    - Global Notification
    - Usage
    - Extensions
        - Extensions can be added from [Visual Studio Azure Devops Marketplace](https://marketplace.visualstudio.com/azuredevops?utm_source=vstsproduct&utm_medium=L1BrowseMarketplace&targetId=ac8f42d0-c08e-4ffe-9a25-f60fabf1dfba)
    - Microsoft Entra
        - Disconnect Directory will remove/change access to organization for current account so dont try this option
2. Security
    - Security Overview
    - Policies
        - Third-part application access via OAuth --> should be turned on
        - Allow Public project --> should be disabled so that any users outside the organization cant access the projects
        - External guest access --> 
    - Permissions
        - Can create new groups and users or modify existing ones
3. Boards
    - Process --> To create customized process
4. Pipeline
5. Repos
6. Artifacts


# Creating projects under an Organization
1. If no projects available, 'Create new project' panel will be available with Project Name, Description, Visibility (Private, Public), Version Control (Git), Work Item Process (Agile, Basic, CMMI, Scrum).
2. If projects available, '+ New Project' button will be available to click then 'Create new project' panel will be available.
3. Fill all the values in 'Create new project' panel and click 'Create' button.







Questions
1. Guest User filter is not filtering external users
1. 



# Reference
https://learn.microsoft.com/en-us/azure/devops/organizations/accounts/organization-management?view=azure-devops

https://azuredevopsdemogenerator.azurewebsites.net/environment/createproject
