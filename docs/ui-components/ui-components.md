---
layout: default
title: Linking to GitHub
nav_order: 3
has_children: false
permalink: /docs/ui-components
---

# Linking to GitHub
{: .no_toc}
PyCharm allows you to connect your GitHub account and manage your GitHub projects directly from PyCharm. This GitHub integration saves you time when managing and contributing to different GitHub repositories.
{: .fs-6 .fw-300 }

---
## TABLE OF CONTENTS
{: .no_toc .text-delta}
1. TOC
{:toc}
---

**Recommended**
{: .label .label-blue }
    Have an existing GitHub account and/or GitHub account credentials ready to ensure a smooth experience.

## Connect Your GitHub Account
Adding your GitHub account to PyCharm can be a confusing process for first-time users. The following steps will allow you to smoothly add your account to PyCharm.

1. From the project workspace, go to **File** -> **Settings** to access the main settings for PyCharm.
    
    ![Connect-GitHub-Account-Step1](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/Link-GitHub-AccountLogIn-1.png?raw=true "File -> Settings")

2.  Go to **Version Control** -> **GitHub**. Click on the *+* button to add a GitHub account.
    
    ![Connect-GitHub-Account-Step2](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/Link-GitHub-AccountLogIn-2.png?raw=true "Version Control -> GitHub")

3.  Choose either **Option A** or **Option B** to log-in to your GitHub account.

    ![Connect-GitHub-Account-Step3](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/Link-GitHub-AccountLogIn-3.png?raw=true "Log-in Options A and B")

    **STOP**
    {: .label .label-red } 
        PyCharm provides two options to add a GitHub account. Both options give the same result.
        A) Log-in with your GitHub credentials
        B) Log-in with personal access token
    
    **RECOMMENDED**
    {: .label .label-blue }
        This guide recommends "Option A" as this option is the quickest method.
        Option B serves as an alternative method should the Option A log-in process fails.
    
### Option A - Log-in with GitHub Credentials
For Option A, your GitHub credentials are needed to sign-in directly from GitHub to add the associated account to PyCharm.

1. Click *Log in via GitHub...* .
   
2. Wait for PyCharm to redirect you to a log-in page.

3. Enter your GitHub account credentials. If successful, the log-in page will redirect you back to PyCharm. 

    **GO**
    {: .label .label-green }
        To proceed to the next step please click on the following link.
        
    [Verifying your GitHub account.](#verify-your-github-account-log-in)
    > [Verifying your GitHub account.](#verify-your-github-account-log-in)

### Option B - Log-in with Personal Access Token
For Option B, a personal accesss token will be generated from GitHub to add the associated account to PyCharm.

1. In a new browser window, go to [GitHub](https://github.com/) and log-in to your GitHub account.

2. Click on *your profile picture* located in the top right corner and click on *Settings* to access your account settings.

    ![GitHub-Account-Settings](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/Link-GitHub-AccessTokens-1.png?raw=true "GitHub Account Settings")

3. Click on *Developer Settings* located below **Account Settings**.

    ![Developer-Settings](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/Link-GitHub-AccessTokens-2.png?raw=true "Developer Settings")

4. Go to **Personal access tokens** -> **Generate new token**.

    ![Generate-New-Token](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/Link-GitHub-AccessTokens-3.png?raw=true "Generate New Token")

5. Create a suitable name for this access token (eg. pyCharmToken). Check the box for the following scope options: **repo**, **workflow**, **read:org**, and **gist**.
   
    ![Access-Token-Settings](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/Link-GitHub-AccessTokens-4.png?raw=true "Access Token Settings")

    **STOP**
    {: .label .label-red }
        Make sure that "repo", "workflow", "read:org", and "gist" are checked off in the box.
        The access token may not work correctly if these four scope options are not selected.   

6. Press *Generate Token* to confirm your access token settings.

7. Copy the access token by clicking on the <span style="color:blue">*blue clipboard icon*</span>.

    ![Copy-Access-Token](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/Link-GitHub-AccessTokens-5.png?raw=true "Copy Access Token")
    
    **CAUTION**
    {: .label .label-yellow }
        Keep your access tokens confidential as the tokens provide access to your GitHub account!
        For security reasons, this newly generated token is "ONE TIME ACCESS" only.
        Ensure you have copied the key, or you will have to generate another access token.

8. Back to PyCharm, click *Log in with Token...* .

9. Paste your access token in the box and press *Add Account* . 

    ![Paste-Access-Token](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/Link-GitHub-AccountLogIn-4.png?raw=true "Paste Access Token")

    **GO**
    {: .label .label-green }
        Proceed to the next step by [verifying your GitHub account.](#verify-your-github-account-log-in)

### Verify Your GitHub Account Log-in
PyCharm allows you to quickly verify

1. Confirm your GitHub account details displayed next to the light blue arrow. Press *Apply* and press *OK* to save your changes. 

    ![Connect-GitHub-Account-Step4](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/Link-GitHub-AccountLogIn-5.png?raw=true "Confirm Settings")


Success! You have added your GitHub account to PyCharm.

---

## Control Multiple GitHub Accounts
PyCharm allows multiple accounts to be added and managed via the Version Control Settings menu. Follow the next steps to learn how to manage multiple GitHub accounts.

1. Press **Ctrl+Alt+S** (default shortcut) to open the **Version Control Settings menu** or follow [Steps 1 and 2 in the previous section](#connect-your-github-account).

2. Add multiple GitHub accounts by pressing the *+* button and follow the same procedure to [add a GitHub account starting in the previous section](#connect-your-github-account).

    ![Control-GitHub-Accounts](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/Link-GitHub-MultipleAccounts.png?raw=true "Control GitHub Accounts")

3. Delete a GitHub account by selecting the chosen account and press the *-* button.

4. Set a default GitHub account be selecting the chosen account and press the *check symbol* button.

Success! You have learned to add, delete, and set default GitHub accounts on PyCharm.

---

## Share Your Project to GitHub
PyCharm allows you to upload and share your project directly onto GitHub. Follow the next steps to learn how!


**STOP**
{: .label .label-red }
    At least one GitHub account must be added to PyCharm before proceeding.
    If you have multiple GitHub accounts, check that the chosen account has been "set to default". 
    This check will ensure that your project will be shared under the correct GitHub account.
  
1. Select and open the chosen PyCharm project that you want to share into your current workspace.

2. In the top menu bar, go to **VCS** -> **Share Project on GitHub**.

    ![VCS-Settings](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/Link-GitHub-ShareProject-1.png?raw=true "VCS -> Share Project on GitHub")

3. In the new window, provide the following project information to create a repositiory on GitHub.

    ![Project-Information](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/Link-GitHub-ShareProject-2.png?raw=true "Project Information")
    
    1. Give a name for the repository where your project will be located on GitHub.
    
        **STOP**
        {: .label .label-red }
            You have the option to set your repository visibility to private by checking "Private" 
            in the box right next to "Repository Name".
       
    2. Provide a project description.
    
    3. Press *Share* to confirm your changes.

4. Provide a commit message and press *Add* to add the project files to the repositiory.

    ![Commit-Message](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/Link-GitHub-ShareProject-3.png?raw=true "Commit Message")

5. Wait for PyCharm to upload your project files to the GitHub repository. A window will pop-up in the lower right hand corner to indicate your project has been succesfully shared on GitHub.

    ![Shared-Project-Confirmation](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/Link-GitHub-ShareProject-4.png?raw=true "Shared Project Confirmation")

6. Verify your project repository by clicking on the project name in the pop-up window. PyCharm will be direct you to the newly created GitHub repository.

    ![Project Repositiory](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/Link-GitHub-ShareProject-5.png?raw=true "Project Repositiory")

Success! You learned how to share a local PyCharm project to GitHub.

---

## Clone an Existing Project to PyCharm
PyCharm allows you to copy an existing GitHub project to your local computer. This feature can be useful when you want to create a new project based on an existing project. Follow to the next steps to learn how!

1. In a new browser window go to an existing GitHub repository page that contains the project of interest.

2. Click on the <span style="color:green">***CODE***</span> button to access the Git url. Click on the clipboard icon to copy the url.

    ![Copy-Git-URL](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/Link-GitHub-CloneRepo-1.png?raw=true "Copy Git URL")

3. Open PyCharm and in the welcome page, click on *Get from VCS* to access the Version Control settings.

    ![VCS](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/Link-GitHub-CloneRepo-2.png?raw=true "VCS")

4. Click on *Repository URL*. Select the **Git** option for Version control.

    ![Paste-Git-URL](https://github.com/sis00337/Pycharm-For-Dummies/blob/gh-pages/assets/images/Link-GitHub-CloneRepo-3.png?raw=true "Paste Git URL")

    1. In the **URL box**, paste the copied Git url.
    
     2. In the **Directory box**, choose where the cloned project will be stored in your local computer.
    
    3. Press *Clone* to copy the GitHub repository to your computer.
    
    4. Wait for PyCharm to copy and load the GitHub repository files to your current workspace.

Success! You have now cloned an existing GitHub project to your local computer.

---

Congratulations!!! You have successfully learned how to configure GitHub accounts and repositories on PyCharm.

Next, try to follow [Working with Version Control](./customization) if you want to learn how to make and save changes to your GitHub repository directly from PyCharm.
