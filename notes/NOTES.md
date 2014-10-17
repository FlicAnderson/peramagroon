{peramagroon} : Project Notes
==============================

**PROJECT AIMS**: 

  * re-organise raw data from several rather disorganised spreadsheets into one (or at least fewer!) useful files
  * sort and tidy these data 
  * re-analyse the tidied data using R statistical programming language, for the analyses outlined in my thesis
  * carry out additional analyses
  * write up (and publish)
  * learn more about: 
    * R stats
    * Data analysis
    * Literate statistical programming and markdown
    * Github / version control
    * Open data
    * Reproducible Research   

### NOTES 

17/10/2014  -  **Initial Set-Up** 

First, I started by creating a fresh repo to hold everything in.  I did this by creating the repo "peramagroon" on the GitHub website (big "+ Create New..." then "New Repository" buttons), selecting "Public" and "add a README file" options, but not adding a license yet, and hitting the big green "Create Repository" button.  

The next stage was cloning it down to my local computer.  Here's how I did it!

1. Open git
2. Go to the location you want to **create your local version** of the repo. If you want it in a separate folder, use `cd` to change directory and `mkdir` followed by the foldername to create the new folder (e.g mkdir peramagroon).
3. Use `ls` to check the folder is empty
4. **Initialise the local repository** by using:
    * `git init`
5. **Link** the local repo you've just initialised (in this case we've called it "origin") to the main GitHub online remote repository by using:
    * `git remote add origin https://github.com/FlicAnderson/peramagroon.git`
6. Now **verify** the repositories are linked, using: 
    * `git remote -v`
7. You should see two lines showing you the fetch/pull urls for your repo
8. Now **pull** the online content of the remote repo (we'll call this "master") on GitHub down to your local repo (aka "origin"), using: 
    * `git pull origin master` 
    * enter your login details
9. Use `git status` to **check** it's all good, and `ls` and `cd` to see what files and folders are there.

If you wanted to get a copy, you would click the "Fork" button to fork the repo and get a copy in your GitHub account, then you could follow these steps, and instead of using my remote repository URL (`https://github.com/FlicAnderson/peramagroon.git`), yours would have your GitHub username instead of mine. 

Easy!

DD/MM/YYYY  -  **Title** 

