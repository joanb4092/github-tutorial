# GitHub Tutorial

_by Joan Balbuena_

---
## Git vs. GitHub
* Git 
    * Keeps snapshots of code and allows you to edit code in the command line. Used to create/edit files, add files, and commit files, where it's all stored in Github.
* Github
    * Stores the code in a cloud where it is able to be altered later on. Used to track changes done in code and can be used to easily collaborate with files.
    *  Requires Git to properly function and store previously edited/created/altered code.

---
## Initial Setup
To be able to use both Git and GitHub, you would need to create 2 accounts, so that you'd be able to see what you have created
First, go to [Github.com](https://github.com)  
Then once you're at the website, you need to click **Sign Up**  
1. Once you clicked sign up, you will need to create your account with a username, email, and password. [If you use an HSTAT Email, your username should your email excluding the '@hstat.org']  
2. After you have filled in the information, you will need to chose a plan. I suggest chosing the free plan unless you'd want to pay for a program you'd most likely never use past High School or College.
3. You will then need to fill in more information on what you would want to use github for, your experience with coding, and how you would describe yourself. Once that's done, click submit.
4. You now have a github account where you are able to check what code you've made and your contribution on your account during the past yearly interval.
5. You are now able to create a Repository, which will require Git to properly show anything on the created repo.
6. To use git, you'd need to go to [c9.io](https://c9.io), and click "Login for existing c9.io customers".
7. You will then see a screen that reads "Sign in to Cloud9". Click on the cat icon button below the Sign In button.
8. Enter your username from github and password.
9. You will then be able to create a workspace which can be used to hold and store code that you write.  
 
#### To Get An SSH Key  
When cloning repositories from github, you'd need to utilize the repositories SSH key in order to be able to copy whatever code is on there
1. Go to a repository of your choosing, and click the green button labeled "Clone Or Download"
 Once you press that, it will provide 2 keys you can copy, an HTML key and an SSH key
2. Copy the SSH key. It should look like this ```git@github.com:bmuellerhstat/01-ruby-basics-lab.git```
3. Once copied, paste that in your workspace with the command ```git clone``` in front of the SSH key
4. You have now Cloned a repository  
```git clone git@github.com:bmuellerhstat/01-ruby-basics-lab.git```


---
## Repository Setup
To create a Repository
1. You will first need to go into your c9.io workspace and create a directory with the command ```mkdir [Repository Name]```.
2. Then use command `cd [Repo Name]` and enter the repository you just created.
3. Once inside the repository, create any file inside that repository, such as a ".md" file, which can be opened and edited by simply double clicking
4. 


---
## Workflow & Commands



---
## Rolling Back Changes