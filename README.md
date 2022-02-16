# A03
## Repository A03 for IS117
### Tutorial: How to get started with Git, Github, and Webstorm.
First, you will want to download Webstorm. The download link will be found here https://www.jetbrains.com/webstorm/download/download-thanks.html.
You will also need to download **Git** from https://git-scm.com/downloads, and select the download option based on your operating system. 
Next, in order to use **GitHub** and all of its features, sign up and create an account at https://github.com/. 
In order to use Webstorm in conjunction with GitHub, the two must be linked up by first locating the system preferences. An easy way to do this is via Ctrl+Alt+S.
Select Version Control, and then under that tab select the option for Git. Enter the file pathway to your Git.exe into the search bar. 
Go back into System Preferences and select Appearance and Behavior. Under this, you will then select System Settings and then Passwords. Here you can set the file path for your passwords.
Now go into Github. At the top right corner, click on the + symbol. Create a new **repository** with New Repository. Set this new Repository to Public and add a README.md file. 
Going back into Webstorm, select VCS and then Import into Version Control. This is how you can create a new repository via Webstorm. 
To import a Repository from GitHub, select Checkout from Version Control and then Git. Enter the repository name and the local path for it. 
To make a Webstorm file, select file, new, HTML File, HTML5 or File, and then StyleSheet. You can then add this Webstorm file to Git via the Add Files to Git option. You then have the option to view the file before sending it out. To confirm the current changes to the file, select **commit**. To **push** a change to a **remote** repository, select VCS, Git, and then Push. Select the committed file, and then press Push. Now the file is added onto GitHub. Using the command $ git **Pull**, you can update your local file with data from the file in the remote repository. When others make changes to your file, they will have to submit a Pull Request. In order to confirm those changes, you will need to **merge** that request by clicking on the request and then selecting from the dropdown which of the merge options you would like to do. Confirm the merge and the changes will be made to the **branch**. Another way changes made by others can be added to the repository without actually making the edit is through a **fetch** using $ git fetch "remote file name".  
A **merge conflict** occurs when two edits are made to the same line and each is sent in as a pull request. To resolve this, you would click on the pull requests and then select Resolve conflicts. 
To set up your GitHub pages, select settings and then check the repository name. Select master branch. With custom domain, you can change the page's link. 
If you want to **clone** your repository, click on the clone option in the main page of the repository. Through this, you have multiple options of how you want your files to be cloned and a URL link. You can then open up Git Bash, changing the current working directory with where you want the clone to be stored in. Type in $ git clone and then the URL from before. Pressing enter to run the command will clone a copy of your files. 
* GLOSSARY
  * Git - Software used for managing and editing files in coordination with others. 
  * GitHub - Version Control Software where users can manage their own files or collaborate with others in different projects. 
  * Repository - where a project and its files exist.
  * Commit - affirms the changes made to a file/project. 
  * Push - command used when uploading local file changes to the file in the remote repository. 
  * Remote - the main online repository that is accessible to all team members. 
  * Pull - requests made by other team members in a project when they want to make changes to a file. 
  * Merge - puts changes from one branch and merges them with the main branch. 
  * Branch - independent line of development for your project code. 
  * Merge Conflict - when two edits are made to the same line. 
  * Fetch - command used to download a copy of changes made by others into the main repository. 
* REFERENCES
  * https://docs.github.com/en
  * Introduction to GitHub and Webstorm by Arthur H. Hendela, Ph.D. Senior University Lecturer, NJIT 
