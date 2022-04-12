# **How to use remote repository and pull request**
    Remote repository uses to make changes in command work or another person's file. 

**GitHub** is a site, where all authorised users can share their projects. Also you can copy and clone files from **GitHub**. But for make command `git push`, when user download his own projects to GitHub, he must be authorised and appoint directory for operation. Process of cloning and copying can be provide without authorisation

## Fork&Clone

There is two commands for copy file from **GitHub**. 

If you have no account on site, you can copy link behind file, go to you local repository, and use `git clone "link"`

After that you need to change directory:
           
    cd "nameofyouractualfile" 
Or, if you authorised on **GitHub**, you can copy needed project to your repository on site with comand `fork`.

## Push&Pull
+ Comand `git pull` makes copy of outsoursed repository to your local. Mane point is merging your actual data with new information. 

+ `git push` makes your changes delivered to outsoursed repository. You must be authorised in site, where repository is.

+ Another way is `pull request`. When you on site **GitHub**, you can push this botton and remove your data to outsoursed repository