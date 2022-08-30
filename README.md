# <p align ="center"> **KT PLAN** :writing_hand:  </p>
_<p align= "center"> plan for ***App onboarding Team***</p>_

---
## **DAY 1**
---
### GitHub & Github Commands :smiley: :nerd_face:
---

>First Create a GitHub Account:
- [How to create GitHub Account](https://docs.github.com/en/get-started/onboarding/getting-started-with-your-github-account)

>Download Git
- [Download Git for Windowa, Mac & Linux/Unix](https://git-scm.com/downloads)

>Install and use Git on Windows
- [Step-By-Step Tutorial for Windows](https://phoenixnap.com/kb/how-to-install-git-windows)

- [Step-By-Step Tutorial for Mac](https://phoenixnap.com/kb/install-git-on-mac)

- [Step-By-Step Tutorial for Linux](https://www.makeuseof.com/install-configure-git-on-linux/)  

---

<h2><span style="color:lightblue">What is Github? :thinking:</span> </h2>

To put it simply, GitHub is a file or code-sharing service that allows users to collaborate with others.  
GitHub is a popular piece of software that is commonly used for version control. It comes in handy when more than one person is working on a project.
Version control lets you keep track of your work and easily explore the changes you've made, whether it's data, coding scripts, notes, or anything else.

![Github working](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2017/11/GitHub-How-to-use-GitHub-Edureka-373x300.png)

---

<h2><span style="color:lightblue">What is Git :thinking: </span> </h2> 

Git allows users to use simple commands to track code changes and manage their projects.  
Git is a distributed version control system for tracking changes in source code during software development. It is intended to help programmers coordinate their actions, but it can also be used to track changes in any set of files.

---

<h2><span style="color:lightblue"> Github Vs Git :thinking: </span> </h2>

GitHub | Git
 ------------ | ------------- 
GitHub is a service. | Git is a software. 
GitHub is a graphical user interface | Git is a command-line tool
GitHub is hosted on the web| 	Git is installed locally on the system
GitHub is focused on centralized source code hosting.| 	Git is focused on version control and code sharing.
GitHub is a hosting service for Git repositories.| 	Git is a version control system to manage source code history.
GitHub includes a free-tier and pay-for-use tier.| 	Git is open-source licensed.

---

# Let's Start with the Commands :memo::pencil:

SETUP and INIT
---

| Command |  Description |
| ------- | ----------- |
`git config --global user.email "[github email]"` | It will set the your email <br> [eg](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/1-9.png)
` git init` | initializes a Git repository <br> [eg](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/2-6.png)
` git clone url`  |create local copy of remote repository(URL)  <br> [eg1](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/4-4.png)   [eg2](https://intellipaat.com/mediaFiles/2019/07/GItCommand12.png)
---
STAGE AND SNAPSHOT
---
---
| Command |  Description |
| ------- | ----------- |
`git status`    |  show status   <br>[eg](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/15-1.png)
`git add [file]`    | add a file as it looks now to your next commit (staging area) <br>[eg](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/5-4.png)
`git add .` | adds all the files to staging area
`git reset [file]` |unstage a file while retaining the changes in working directory <br>[eg](https://static.javatpoint.com/tutorial/git/images/git-reset3.png)
`git diff` |diff of what is changed  <br>[eg](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/9-2.png)
`git commit -m “[descriptive message]”` | commit your staged content as a new commit snapshot   <br> [eg](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/7-3.png)
`git commit -am "[description message]"` | adds and commits together(only applicable to the files that are already pushed on remote repo) 
---
BRANCH
---
---
| Command |  Description |
| ------- | ----------- |
`git branch` |list your branches. a * will appear next to the currently active branch  <br>[eg](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/23.png)
`git branch -d [branch name]` | deletes the branch  <br>[eg1](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/25.png) [eg2](https://intellipaat.com/mediaFiles/2019/07/GItCommand14.png)
`git branch [branch name]` | creates a new branch <br>[eg](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/24.png)
`git checkout -b [branch name]` |create a new branch and switch to it <br> [eg](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/28.png)
`git checkout` |switch to another branch <br>[eg](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/27.png)
`git branch -m [old branch name] [new branch name]` | rename a local branch 
`git merge [branch name]` | merge the specified branch into active branch  <br> [eg](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/31-1.png)
`git merge [source branch] [target branch]` | merge a branch into a target branch <br> [eg](https://intellipaat.com/mediaFiles/2019/07/GItCommand25.png)
`git log`| show all commits in the current branch’s history<br> [eg](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/18-768x293.png)
---
UPDATE
---
---
| Command |  Description |
| ------- | ----------- |
`git remote add [alias] [url]` |add a git URL as an alias <br> [eg](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/32.png)  
`git fetch [alias]` | fetch down all the branches from that Git remote  <br>[eg](https://intellipaat.com/mediaFiles/2019/07/GItCommand27.png)
  `git push [alias(origin)] [branch name]` | push branch to the remote repository  <br> [eg](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/33.png)
`git push -u origin [branch name]` | push changes to remote repo and remembers the branch  <br> _-u: upstream_
`git pull` | fetch and merge any commits from the remote repository to local repository <br>[eg](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/38.png)
`git rm [file name]` | This command will delete the file- <br>[eg](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/16-2.png)

---

# **DAY 2**

<h2><span style="color:lightblue"> What is PR(Pull Request)? :thinking: </span> </h2> 
Pull requests let you tell others about changes you've pushed to a branch in a repository on GitHub. Once a pull request is opened, you can discuss and review the potential changes with collaborators and add follow-up commits before your changes are merged into the base branch.

---
<h2><span style="color:lightblue"> What is forking? :fork_and_knife: </span></h2>
A fork is a copy of a repository. This is useful when you want to contribute to someone else's project or start your own project based on theirs.  
Forking a repository allows you to freely experiment with changes without affecting the original project.
It is a concept of making copy of the main repository to your account so that you can make modifications in it. You can Submit pull request to the main repository with the modifications. It will make sure that the main repository is prevented from unwanted changes.

___

<h2><span style="color:lightblue">What is merge conflict and how to resolve it? :thinking: </span></h2>

Merge conflicts happen when you merge branches that have competing commits, and Git needs your help to decide which changes to incorporate in the final merge.  
To resolve a merge conflict, you must manually edit the conflicted file to select the changes that you want to keep in the final merge.   
There are a couple of different ways to resolve a merge conflict:

    -If your merge conflict is caused by competing line changes, such as when people make different changes to the same line of the same file on different branches in your Git repository, you can resolve it on GitHub using the conflict editor.   

    -For all other types of merge conflicts, you must resolve the merge conflict in a local clone of the repository and push the change to your branch on GitHub. You can use the command line or a tool like GitHub Desktop to push the change. 
___

<h2><span style="color:lightblue"> What is read md file? Why is it used? :thinking: </span></h2>

A README file is an essential guide that gives other developers a detailed description of your GitHub project.
It is a text file describing what the project is about, what it does, how to use the project, and other information regarding the same.
The readme file is used to explain what is uploaded and how we can install or use it. It even allows the uploader to add images and videos to help the reader navigate through the project. A well-written readme file is more important if you intend to show these projects in your resume.

---

# Let's Start with the Basix Syntax of MarkDown :memo::pencil:

Basic Syntax
----
___

| Element | Markdown Syntax |
| ------- | ----------- |
Heading |	# followed by the text (upto 6#s)<br>eg: <br> # H1 <br> ## H2 <br> ### H3
Italic |	Wrap the text with 1 asterisks/underscores  <br>eg:*italicized text*
Bold | Wrap the text with 2 asterisks/underscores<br> eg: **bold text**
Simultaneously Bold & Italic | Wrap the text with 3 asterisks/underscore <br>eg: ***Bold & Italic***
Strike Through | Wrap the text in two tildes <br>eg: ~~Strikethrough~~
Blockquote	| Precede the first line of block quote with angle bracket <br>eg: >blockquote
Ordered List	| 1. First item <br> 2. Second item <br> 3. Third item   
Unordered List	   | - First item <br> - Second item <br> - Third item  
Code	| To reference snippets of code we start and end the code with backticks <br>eg: `code`  
Horizontal Rule	| To split blocks of texts visually we use 3 or more hyphens/asterisks/underscore <br>eg ---  
Link	| Wrap link text in brackets [ ], and then wrap the URL in parentheses ( ) <br>eg: [title](https://www.example.com)
Image	| Start with ! followed by alt text in [] and URl in () <br>eg: ![alt text](image.jpg)
