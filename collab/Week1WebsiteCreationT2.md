# Website Creation - GitHub
Once you have a repository begun on GitHub, you can choose to edit your files directly through GitHub's website or you can use an external coding software. I will be using Visual Studio Code to complete my updates to the repository.

*Below I have included brief instructions on how to edit files on GitHub:*
1. Log in to GitHub and navigate to your chosen repository - mine is carolbuckingham/dumoine-river
2. Once on the main page for your repository, you can create files by clicking "Add file" and choosing the "Create new file" option. 
N.B. if you've already created a file on your computer, you can add it directly via the "Add file" menu by clicking "Upload files" and then selecting the relevant files on your drive.
3. GitHub will automatically start the next page with your cursor in the "Name your file..." block, simply type in a file name and an appropriate file type and you can begin to code your file. If you would like to nest the file within another folder, type the folder name (if it already exists then it will be stored under that folder, if not GitHub will create a new folder to house your file) and then a forward slash ( / ) and then enter your file name and file type.
4. After you've completed adding to the code block of your file, scroll down the page and add an appropriate title and description for the commit to the directory. GitHub will often auto generate a title based on the work you have done - like creating or renaming a file, editing or removing lines, etc.
5. Ensure that the file is committing directly to the main branch! We do not have other branches in our repository.
6. Click the commit button to save your changes.

### Connecting GitHub to Visual Studio Code
This can be done at any time prior to working on the repository with Visual Studio Code.
1. Ensure that Visual Studio Code is NOT running.
2. Go here and download GIT → https://git-scm.com/download/win
3. Start the installer and pick the following options:
    - Default editor – it wants to use Git something-or-other. There will be a dropdown, change it to Visual Studio Code.
    - Default directory – there will be two options – the default is “Master”, we need to select the 2nd option and enter “main” into the input field. This will make the default new branches line up with GitHub.
    - Use the defaults for everything else.
4. From the Start menu, launch Git Bash. Type the following with the name and email sections filled out with your information and hit enter after each line:

> git config –global user.name "Your Name"

> git config –global user.email "your@email.address"

5. To confirm that this worked, type the code below. If the last two lines of the list generate your input, go ahead and close Git Bash.

> git config --list

6. Continue to the next section to contine connecting to Visual Studio Code.

## Cloning repository to Visual Studio Code.
This section assumes that Visual Studio Code is installed along with the Git toolset (see https://marketplace.visualstudio.com/items?itemName=donjayamanne.git-extension-pack). It also assumes that the user has already linked their GitHub account to VSC.
1. Open Visual Studio Code.
2. see guide from last semester for how to add a GitHub account to VSC!

## Creation and organization of supplemental files
1. within visual studio code..

## HTML file skeleton
***I started with the head element of the pages since this will be the simplest to complete and should be done first to clarify the subject matter of each webpage.***
1. add in html, head, and body elements
