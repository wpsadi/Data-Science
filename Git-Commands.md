# to show all files (including Hidden files)
ls -a `-a stands for all` 

# to show the remote
git remote -v `-v stands for verbose - means to show URLs also`

# to remove the remote origin
git remote rm origin

# to add the origin
git remote add origin https://github.com/username/repo.git `It requires 2FA`

    ==== if you want to add with completing 2FA ====
    create a classic token from developer Options and then create a token 
    keep in mind to alow Read/Write/Commit and Admin access of public key
    then add the token in the url like this

    git remote add origin https://<token>@github.com/username/repo.git 


# to intitaila Repositor
git init

# to know untracked file
git status

# to add file to tracking
git add <file_name> 
or 
git add .  

# add branch name
git branch -M main

_Remember Commit is done before pushing_

# to commit the files
git commit -m "message" 
or
git commit -m "message" -a

# to push on origin's main branch
git push -u origin main

# To set credentials in git
git config --global user.name "your name"
git config --global user.email "your email"