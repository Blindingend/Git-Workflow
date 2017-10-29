# What is Git Workflow
One of the earliest and widely adopted work processes is Git flow.
## Features
It got two main features

### 1.The project has two long-term branches
![IMAGE](http://www.ruanyifeng.com/blogimg/asset/2015/bg2015122302.png)
> *  master
> * develop

The former is used to store external releases, and any time it is available in this branch, it is a stable release
The latter is used for daily development and storage of the latest development

### 2.The project has three short-term branches
> * feature branch
> * hotfix branch
> * release branch

Once developed, they are merged into **develop** or **master** and then deleted.

# Why do we use Git Workflow
When we talk about this issue, there are actually two issues that we need to talk about
## 1.Why we have to use version control 
### Teamwork
Teamwork is quit important in development, especially in large projects, it is important to maintain cooperative cooperation. Version control tools enable a team to collaborate in an organized manner.
### Store Correctly
Each version control system corresponds to a single project. Therefore, there is only one version in your native place, which is the current working version of this project. In addition, all previous versions and changes have been stored in the version control system in an orderly manner. When you need it, you can always check out any previous version and get a snapshot of the entire project.
### Return to Previous Version
We all know that there is no such thing as a penitence。 But with version control tools, we can easily return to previous version if we made some mistakes. It's wonderful to got penitence.
### Know What happened
Whenever you submit a new change to the project, your version management system will ask you to add a short description of the change. In addition to this (if it's a code or a text file), you can also see a detailed control of the content before and after the change. This will also help you understand the development relationships between versions and versions.
## 2.Why we choose git
### save your time
Git works in a flash(not works in a flash, hhh), seconds matters when you need to use something frequently in long-term.
### work offline
You can work when you can't connect to online remote central respository. Almost everything can be done simply on your local machine. For example, submit, view your project history, merge, or create branches, etc. As for where to work? When will you work? Git won't impose any restrictions on you.
### Avoid confusion
Separation of concerns can provide a clearer picture of what is going on. When you work on function A, there should not be anyone who is affected by your unfinished code. What if that function is completely unnecessary? Or did you notice that you were completely wrong when you submitted some of the changes to it? Branching functions can solve these problems. Of course, other version control systems have branches, but Git really makes it faster and easier.

### Conform to the trend

Smart developers should follow the trend. Git is being used by more and more well-known companies and open source projects such as Ruby On Rails, jQuery, Perl, Debian, Linux kernel, and so on. Having a large user community is a big advantage, because there are often many systems to drive his development. A lot of tutorials, tools and services make Git more attractive.

# How can we use Git Workflow
## 1.Command line
It's to fussy to list all commands here, so I attached a link to the common commands
[>Click here<](http://www.jianshu.com/p/0f2ffa404ac1)

## 2.Sourcetree
![IMAGE](https://www.sourcetreeapp.com/dam/jcr:f32681c1-355d-4806-b29c-319b0c6ecb06/Sourcetree-blue.svg?cdnVersion=ht)

### Simpler and easier with GUI

![image](https://www.sourcetreeapp.com/dam/jcr:580c367b-c240-453d-aa18-c7ced44324f9/hero-mac-screenshot.png?cdnVersion=ht)

You can learn more to view its official website ———— [Sourcetree](https://www.sourcetreeapp.com)