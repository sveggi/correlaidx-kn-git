# git-newbie-playground
This is a repository for Git newbies to fork and play with. 


# Setup Git and GitHub
⚠️ Setting up Git on your local machine / laptop can be a bit of a pain and might not work the first time. I tried to describe a way that _should_ work. That being said, I could not test it extensively (because Git is already set up for me and I don't have access to a Windows machine). Please don't give up - once you have set it up correctly you don't need to do this again. ⚠️


## 1. Create GitHub account
- Create a GitHub account if you have not already: https://github.com/join

## 2. Install Git

### 2.1. Windows
- install Git: https://git-scm.com/download/win
- If you have Git installed already, please make sure that you have at **least version 2.29** (required for storing credentials securely): 
```
git version 
```
If you do not have at least version `2.29`, please update Git: 

```
git update-git-for-windows
```

### 2.2. Mac
- install Git, see [here](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

### 2.3. Linux
- Git should already be installed on your machine. To check, please run: 
```
git version
```
If not, please google "install git {your distro}" and you should find out how to install it.

## 3. Introduce yourself to Git

Open a terminal (Mac / Linux) or Git Bash (Windows).

Copy each of the following commands, adapt the name and email address (the email address should be the address you used for your GitHub account), and hit enter.

```
git config --global user.name 'Jane Doe'
git config --global user.email 'jane@example.com'
```

## 4. Git going! 




# Resources
## Read
- [Git Book - Git Basics Chapter](https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository): very good overview! 
- [Happy Git with R](https://happygitwithr.com/): R in RStudio
- [Git our sh*t together - VSCode](https://gost.netlify.app/en/2019-12-01_correlaid-meetup-berlin/#1): a similar workshop to this one but with the excellent Git VSCode extension

## Practice 
- [Git Katas](https://github.com/muses-code-js/git-katas): command line Git through focused exercises
- [Learn Git Branching](https://learngitbranching.js.org/): interactive exercises to learn git branching
