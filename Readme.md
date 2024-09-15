Fork the repository xNORAGAMIx/NEXUS_DROP

Clone the forked project YOUR_github/NEXUS_DROP 

    git clone <your_forked_repository_url>

Configure git for pulling from base repository

    git remote add upstream <url_of_xNORAGAMIx/NEXUS_DROP>
    git fetch upstream

Merging from base repository to your repository

    git checkout <branch_name / main> {your repository}
    git merge <upstream/main> {base repository branch name}

Push to your repository

Creating Pull Requests
1. Head to base repository
2. Choose New Pull request
3. base repository , head repository - your repo

Steps for initialization
1. run npm install 

config folder in server is for the database connectivity

    use .env for ports and connection strings and secret keys

    if you are working on backend, for now just connect to your local mongoDB server, later we can use Mongo Atlas

I think it will be better to work on individual branches for now.

Create a main branch with your name - , then

Create a branch for a feature you are working on->

if you are working on frontend/homepage ->

    git branch <your_branch_name> (to create a new branch)
    git checkout <your_branch_name> (to switch to branch <your_branch_name>)
    code your changes
    git add . or git add filenames(you worked on)
    git commit -m "Commit message"
    git push origin <your_branch_name>

Once you have completed working on your branch/feature ->

    switch to your main branch
    merge the feature branches -> git merge <your_branch_name>

Delete the feature branch once you are done with it -> git branch -d <your_branch_name>

Push/commit using VSCODE or terminal

if on vscode -> commit and push

if you are using terminal

    code your changes
    git add . or git add filenames(you worked on)
    git commit -m "Commit message"
    git push origin main

P.S - Download any dependencies you need, I have just added the basic ones.

Can someone add the files and initialize the client file with vite?
My internet is taking hours to install using npm!