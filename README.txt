# git_commit
Instructions on how to commit to Git from Pycharm and Jupyter 

1. COMMITING from Pycharm:
    a) Open the PyCharm project that you want to commit changes to Git.
    b) In the toolbar, click on the "Version Control" icon (it looks like a square with a curved arrow inside).
    c) Click on the "Commit" button. This will open the "Commit Changes" dialog box.
    d) In the "Commit Message" field, enter a brief description of the changes you have made.
    e) Select the files you want to commit by checking the box next to each file name in the "Files" tab. You can also select all files by clicking the checkbox next to "Unversioned Files" or "Changed Files".
    f) Review the changes in the "Diff" tab to ensure that you are committing the correct changes.
    g) Click the "Commit" button to commit your changes to Git.
    h) Finally, push your changes to the remote repository by clicking the "Push" button in the "Version Control" toolbar.

2. CLONING from Git into Pycharm 
    a) Open PyCharm and click on "Get from Version Control" on the Welcome screen, or go to "File" -> "New Project" -> "Get from Version Control" in an existing project.
    b) In the "Get from Version Control" dialog box, select "Git" as the version control system.
    c) Enter the URL of the repository you want to clone in the "URL" field. You can find this URL on the repository's homepage on GitHub or another Git hosting service.
    d) Choose the directory where you want to store the repository on your local machine by clicking the "Directory" field.
    e) Click "Clone" to start the cloning process. PyCharm will download the repository and create a new project with the repository as the root directory.
    f) Once the cloning is complete, you can start working with the project in PyCharm.

3. COMMITING from Jupypter 
    a) Open your web browser and go to the GitHub repository that you want to clone.
    b) Click on the "Code" button and copy the HTTPS URL of the repository.
    c) Open Jupyter Notebook or JupyterLab and navigate to the directory where you want to clone the repository.
    d) Click on the "New" button and select "Terminal" to open a new terminal session in Jupyter.
    e) In the terminal, type "git clone" followed by a space and then paste the HTTPS URL of the repository that you copied earlier.
    For example, if the HTTPS URL of the repository is "https://github.com/username/repository.git", the command would be:
    git clone https://github.com/username/repository.git
    f) Once the cloning is complete, you can navigate to the repository directory and start working with the files in Jupyter.
    
4. CLONING to Jupyter 
    a) Open your web browser and go to the GitHub repository that contains the notebook you want to clone.
    b) Click on the notebook file that you want to clone to view it.
    c) Click on the "Raw" button to view the raw version of the notebook.
    d) Copy the URL of the raw notebook file.
    e) Open Jupyter Notebook or JupyterLab and navigate to the directory where you want to clone the notebook.
    f) Click on the "New" button and select "Terminal" to open a new terminal session in Jupyter.
    g) In the terminal, type "wget" followed by a space and then paste the URL of the raw notebook file that you copied earlier.
    For example, if the URL of the raw notebook file is "https://raw.githubusercontent.com/username/repository/main/notebook.ipynb", the command would be:
    wget https://raw.githubusercontent.com/username/repository/main/notebook.ipynb
    h) Once the download is complete, you can open the notebook file in Jupyter and start working with it.
