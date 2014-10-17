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

--------------------------------------------------------------------------------

17/10/2014  -  **ORCiD** 

I decided to sign up to [ORCiD](http://orcid.org/) in order to get hold of my own personal "Open Researcher and Contributor ID" - a persistant nonproprietary alphanumeric code which will uniquely identify me as a scientific/academic author.  This means any publications I make can be traced back to me, instead of getting confused with any other F.L.Andersons, or similar hassle. 

It's an easy process to sign up, and anyone can do it.  You don't need to be affiliated with any institutions, although you can add those when you have an account.  To register, go [HERE](https://orcid.org/register) and fill in your details.  It will then generate you a shiny new and unique number.  You can then use this wherever you like, and it will stay with you despite name changes, location changes, etc.  Handy stuff!  You can also use keywords to describe your field or your work.

Check me out: http://orcid.org/0000-0001-8778-6779

So far I haven't got around to filling out my employment/education details, but I'll get this done soon.

--------------------------------------------------------------------------------

17/10/2014  -  **License** 

I decided to add a license to let people know what they are and aren't allowed to do with my data and code.  I want to contribute to open data, but I also want people to recognise my contributions and cite me as necessary.  So I decided to go with a "Creative Commons Attribution-NonCommercial 4.0 International License".  

I chose that [HERE](https://creativecommons.org/choose/).  All you have to do is click what kinds of things you'd like people to do (or not) with your stuff, and optionally add a few details such as the name of the thing and who you are, and it generates a little badge you can add to your webpage.  

Here's mine: 

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Peramagroon Mountain Vegetation Project</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/FlicAnderson/peramagroon" property="cc:attributionName" rel="cc:attributionURL">Felicity Anderson</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.

--------------------------------------------------------------------------------


17/10/2014  -  **Citable Code / DOI** 

So I have a unique identifier (my ORCiD number), but what about my code?  What about any data I put up?  I want that to be citeable too.  This is entirely possible, by means of the [Zenodo](https://zenodo.org/) service, which allows researchers to share and showcase their research.  You can link it up to your ORCiD number too, and your GitHub account.  Which is exactly what I did!

There's a great tutorial aimed at researchers who want to cite GitHub repositories in academic literature, and it shows you to how to set things up here: https://guides.github.com/activities/citable-code/ 

1. **Choose your repo** - in my case, that would be `peramagroon`.  
2. Go to [Zenodo](https://zenodo.org/) and **sign in to Zenodo**.  It'll ask if you want to login with your GitHub account, which you do!    
3. When GitHub asked for permission to **authorize** Zenodo to link up and configure 'webhooks', I clicked "Authorize application".   
4. It then shows you a list of repos, and you toggle the one you want to archive (ie. peramagroon) to "ON".   
5. **Check** in the "Webhooks & Services" tab on your repo, and make sure that a new webhook has been set up to link your repo to Zenodo.  If everything worked, you don't have to do anything else about webhooks.    
6. To test the whole system out, you need to **create a new ['Release'](https://help.github.com/articles/about-releases/)** to trigger Zenodo to archive your repo. You can do this by clicking on the little tag-icon and the bit that says "0 releases" if you haven't already created any.  You fill in the new release form, giving the release a version number (eg. v1.0 or similar) and then click **Publish release**.   
7. On Zenodo, this should have added the new release to your Upload page.  **Edit** the details for the release to include any more information you want archived about it.    
8. Click **Submit** to mint the DOI.  
9. You can now click on the grey and blue DOI badge to **get the badge URL**, which you can then paste into your GitHub repo, like this: 

[![DOI](https://zenodo.org/badge/doi/10.5281/zenodo.12271.png)](http://dx.doi.org/10.5281/zenodo.12271) 

And now my repo is citeable!!

--------------------------------------------------------------------------------

DD/MM/YYYY  -  **Title** 


--------------------------------------------------------------------------------

DD/MM/YYYY  -  **Title** 


--------------------------------------------------------------------------------

DD/MM/YYYY  -  **Title** 


--------------------------------------------------------------------------------
