# CroftMicroLab
Get yourself set up locally, You should only need to do the following steps once on a device:
1. If you haven't already make a github account (https://docs.github.com/en/get-started/onboarding/getting-started-with-your-github-account)
2. Download and set up git so you can use it in your local computer
    a) To set up git locally please see the following instructions (https://docs.github.com/en/get-started/quickstart/set-up-git)
        In your local terminal
        -Download and Install the latest version of git
        -Set your username in Git (https://docs.github.com/en/get-started/getting-started-with-git/setting-your-username-in-git, follow instructions for setting your Git username for every repository)
        -Set your commit email address in Git (https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-email-preferences/setting-your-commit-email-address, follow setting your commit email address in Git instructions)
3. Authenticating Github with Git (continue further down on the same page, https://docs.github.com/en/get-started/quickstart/set-up-git)
    If you clone with HTTPS you can cache your GitHub credentials in git using a credential helper (https://docs.github.com/en/get-started/getting-started-with-git/caching-your-github-credentials-in-git)
        a) Install GitHub Cli
        b) In the commandline enter gh auth login, see steps in link for more specifics
4. Install VsCode(https://code.visualstudio.com/) and install Live Server as an Extension 
5. Within your terminal navigate to where you want to store the files locally, you can also do this within file explorer and then say to open that folder in terminal. 
    Then run this command in terminal: git clone https://github.com/tcr0fts/CroftsMicroLab.git 
    If this was successful you should now see all the files on your computer where you cloned them
6. Open your project in VSCode by clicking on the folder from file open folder

Editing the project, Going Forward now that the environment is setup:
1. Once you have the files set up and can open them in VSCode, you should be able to edit them from there, changes you make will be tracked on the left on the branch node icon, labeled source control
2. You can see changes you have made locally by clicking Go Live on the bottom right, changes can be seen on a local server that runs
3. If you are happy with any changes you make and want to deploy them live to the website write a commit message in the source control and click commit. A prompt will ask you if you want to commit all files, you would say yes.
4. It will then show an arrow for pushing up and syncing the changes on git hub, you would click the sync arrow and ok to any prompts. If you navigate to the github repo you should see that your commited changes and within about 5 minutes you should see any changes you made on live.

You can also do steps 3 and 4 within VSCode terminal(terminal, then new terminal to open) with the following commands:
git commit -m"message here"
git push origin main

Other Notes: 
If you would like to add other collaborators to have write access to the website you can navigate to settings and then collaborators and add them there. 
If others are not given write access they will not be able to commit directly, instead they will need to fork from the repo, make a clone of that fork, commit and push to that branch and then open a pull request that can then be approved or denied to make those changes in the main repository 