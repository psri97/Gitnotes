1st class->18-10-2022
git -> it is a git client software which helps us to configure repositories, managing the code using git.
Source Code Management (SCM) -> To store our projet code 
Examples:We can use to store our code GitHub, Gitlab , BitBucket depends on our project requirements.
Github -> it is a collection of repositories which are used to store our code.
Local machine  
Dev-1 -- code -- feature-1 -- stored locally..!  
Dev-2 -- code -- feature-2 -- stored locally..!  
storing code in local is not a recommended way...!
remote repo
- code is storing in a centralized way
- code sharing(distribution) is easy 
- storing code in a safe and secure place
- code tracking
- versioning
- phased manner deployment v1, v2 

2nd class->26-10-2022
Types of repos?
what is local repo?
what is remote repo?
how to create a local repo?
what is working tree?
what is staging area?
what is commit in git?

- Local Repo
- Remote Repo
     Public and Private repos
Reference links:
- Basic Git workflow
    https://evanwill.github.io/get-git-b/content/3-workflow.html

    working directory - staging Area - Local-repo 

  git init -- Initialize repository in your local machine
  git status 
  git add - staging area 
  git commit -m "added file" -- Local repo
  git remote -v -- list out the remote-repos to that particular local repo
  git remote add origin git@github.com:rajeshrj94/test.git
  git remote -v -- it should populate the remote only after executing the above command
  git push origin <branch_name>