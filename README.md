# A03
## Webstorm Tutorial
1.First, one has to go to [Jetbrains Licenses](https://www.jetbrains.com/community/education/#students). This is where you get a license to use jetbrains and Webstorm. Here, you click on the "For Student and Teachers" button and then click "Apply Now". Then you click "Official Document" and fill out your information. Take a picture and submit your school ID and then wait until jetbrains contacts you that you have received the free license.
2. Once you have aquired a free license, download Webstorm here: [Webstorm](https://www.jetbrains.com/webstorm/promo/).
3. Once you installed Webstorm, link your free license to the application from the link you receive in your email. Create an account and enter your username and password into the Webstorm application to link your account to the free license. 
## Connecting Webstorm to Github
1. Download Git: [Git](https://git-scm.com/downloads).
2. Double click the Git file and install the application. Get Git Bash.
3. To connect Git to Webstorm, start up Webstorm and check for updates just in case it is not fully updated (Help-->Check for Updates).
4. Press Ctrl,Alt,S on your keyboard to go to Settings. 
5. Go to Version Control, and then click Git. Click test for the path to Git. The text in the test box should be "C:\Program Files\Git\cmd\git.exe". If it tells you the version number of Git, you are successfully connected.
7. Click OK to exit.
8. Click "Create New Project" on the Webstorm main page, pick a safe location for your new file, and then title it whatever you like in the area in the location link where it says "untitled". Click "Create".
9. Click File -> New -> HTML File. Name the file "index" in lowercase.
10. Edit the HTML file however you please, then, click VCS-->Create Git Repository. Find a location for your repository and then click "OK".
11. Commit this to Git by going to "Git" on the top of the screen, and clicking "Commit". If this is the first commit you have made, you will have a dialog box open. Set the Git username and email by using your school edu email. Set and Commit. Also, make sure to click on the file you want to commit, which is index.html, and add a commit comment of your liking.
12. Then, go to Git-->Share Project on Github.
13. Click Share. You should get a message saying you have successfully shared your project on Github.
14. Now, you can go to [Join Github](https://github.com/) and click and see that your file is there once you login (with your school email and password).
15. Click on your new repository and go to "Add File" and then "Create New File". Name it README.MD. Add text and then commit to add it to the list.
## Making a Change in Webstorm
1. If you want to make a change, change some text in your html file. Go to Git-->Commit. Add the commit comment and then click "Commit".
2. Push the change to Github by clicking Git-->Push.
3. When it says "Push Rejected", click "Merge" in order to synchronize Github and your local machine. Now, you can also see your README.MD file locally.
4. The new line in index.html is now revised.
## Create Repository from Github
1. Go to [Join Github](https://github.com/) and log in. 
2. Click the "+" sign in the upper right corner. Choose "Create New Repository". Make it public and add the readme.md file. Click "Create".
3. If you want to import this repository to Webstorm from GitHub, click VCS, Checkout from version control, Git. 
4. Enter Github repository name and local path name.
## Pages on Github
1. Within your repository, click Settings.
2. Select “Master branch”
3. Copy the Github.io URL into a browser
## Glossary
* **Branch**: a copy of a Git project that you can change and then add to original project ("main" is the main branch where code is stored)
* **Clone**: downloading an already made git repository into your computer; when you clone it, you now have your own local version of the repository 
* **Commit**: saving changes of a file into the local Git repository, or just changing files
* **Fetch**: downloads commits, files, and refs from a remote repository into your local repository; used to see what everyone else is working on
* **GIT**: a free and open source software for distributed version control and tracking changes in a set of files 
* **Github**: a website for software development and version control using Git
* **Merge**:  takes changes created by a git branch and integrates them into a single branch; combines two branches
* **Merge Conflict**: happens when people make different changes to the same line of the same file, or when someone edits a file when it is deleted; also happens when merging branches with competing commits
* **Push**: sends your committed changes to a remote repository 
* **Pull**: when you fetch in changes and merge them
* **Remote**: version of a repository/branch that is on a server (such as GitHub.com)
* **Repository**: most basic element of GitHub; contains all of a project's files, and stores each file's revision history
## Reference List
1. [IntroToGitHub-20190318 (1).pptx](https://github.com/juliasklodowska/A03/files/9701548/IntroToGitHub-20190318.1.pptx)
2. [ExtraInstallationInstructions-20200214.pdf](https://github.com/juliasklodowska/A03/files/9701550/ExtraInstallationInstructions-20200214.pdf)
3. [Branch Definition](https://www.howtogeek.com/714112/how-to-create-a-new-branch-in-github/#autotoc_anchor_0)
4. [Clone Definition](https://www.educba.com/github-clone/)
5. [Commit Definition](https://www.geeksforgeeks.org/what-is-git-commit/)
6. [Fetch Definition](https://www.atlassian.com/git/tutorials/syncing/git-fetch#:~:text=In%20review%2C%20git%20fetch%20is%20a%20primary%20command,local%20repository%20to%20the%20state%20of%20a%20remote.)
7. [Git Definition](https://www.git-scm.com/book/en/v2/Getting-Started-What-is-Git%3F)
8. [Github Definition](https://kinsta.com/knowledgebase/what-is-github/)
9. [Merge Definition](https://www.atlassian.com/git/tutorials/using-branches/git-merge#:~:text=Git%20Merge%20Merging%20is%20Git%27s%20way%20of%20putting,branch%20and%20integrate%20them%20into%20a%20single%20branch.)
10. [All other Definitions](https://docs.github.com/en/get-started/quickstart/github-glossary)
