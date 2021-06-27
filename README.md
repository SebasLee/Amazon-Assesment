# Amazon-Assement

# Github and Repositories

Github is a code-hosting platform that can track and save code in real time. It connects to a user's code editor and allows open-source access to that user's repository (the space where code is stored). In other words, Github allows for collaboration between different users on the same projects. 

One popular method Github users use to collaborate on repositories is called **Forking**. Forking is when users take a copy of a repository into their accounts and clone it into their local computers to make edits. This method is in contrast to direct **Cloning**, which forgoes forking and only clones down the original repository.
<br></br>
<p float="left">
    <img src="./images/Git-Clone.jpeg" height="400" />
    <img src="./images/fork.png" height="400" />
</p>
The image on the left illustrates the developer process cloning without forking, while the right illustrates the process with forking.
<br></br>


Cloning the original repository can quickly update projects since invited users can push changes at anytime. In group projects however, this can lead to unwanted changes in the main code if users are not communicating effectively. Therefore this process is suited better for groups that decentralize their assignments. 

Forking repositories allows for wider access to github users since they can edit any public project with supervision. Merging edits with the original repository occurs only with that repository owner's permission. It leaves room for reviewing code and ensuring changes are satisfactory.

This user guide will focus on how to Fork repositories and implement changes. It will center around macOS systems.
<br></br>
# How to Fork Github Repositories
To fork a repository, first locate a repository to work on through public access or an invititational from the owner. Once on the home page for the project, click the Fork button located in the top-right corner of the browser and near the profile icon.
<br></br>
<img src="./images/1st.jpeg"/>
<br></br>

This will create the copied repository that can be edited. The top left corner of the page will now indicate the repository is under the user's account. 
<br></br>
# Cloning Repository and Editing Code

The **terminal** is a computer interface that connects to the **command line**, where users can effectively communicate with their computer's operating system and outside sources. It is key to connecting Github accounts to code editors.

To gain access to the code, click on the green **Code** button in approximately the upper-center-right of the page, indicated by the red circle. 
<br></br>
<img src="./images/2nd.jpeg" />
<br></br>

A pop-up will appear with options and a HTTPS URL link indicated by the green circle. Copy the link. Next, open the terminal and navigate with ``cd`` (change directory) to the desired location for the repository's code.

Once an appropriate location is found, type in ``git clone`` followed by the copied HTTPS link. Then press the enter keyword.
<br></br>
<img src="./images/cloneterminal.png" />
<br></br>

The terminal will form the repository into the computer. The URL can be verified with the ``git remote -v`` command, which will show the repository under the Github username. To initiate the project, change directory into the repository and open it with the preferred code editor (``code .`` for VScode). 