### **What is a Git repository?**

Time to talk a bit of the filesystem?

Many of the pitfalls the students went through last year were around not understanding the core pieces of vocabulary. For example, some students weren't familiar with basic elements of the file system:

*student: Is a folder the same as a directory?*

This non answered questions leads them to more confusion with upstream terminology that involves a step towards abstraction:

*student: Is a (Git) repository also a synonym of a directory?* *They both look like folders, they should be the same...*

Making the students actively work with these terms is vital to avoid misconceptions to operate over their learning. If these concepts are not clear at this point could create an "snow-ball effect" and evolve to errors more difficult to detect. For example, I have helped to debug errors produced by creating Git repositories inside other Git repositories, mainly because the students were not aware they were doing so.

Link to Stack Overflow question

One question to possible solve that is:

-   Why it is not a good idea to clone the Git repositories you are using for the labs inside the cloned folder of the course?


----

Features based development

-   good practices

-   `master` replaced by `main`

This could be interesting to include due to many open source projects that started before the change will still conserve `master` as the main branch

As an example imagine that you want to contribute to this [multilingual glossary for computing and data science terms](https://glosario.carpentries.org/) created by The Carpentries, an inclusive community willing to teach data and coding skills. If you explore the GitHub repo of the project (https://github.com/carpentries/glosario) you will see a file called `CONTRIBUTING.md` where it is explained how someone can add new terms to the glossary. In general, when you want to contribute to a public repository as this one, you will have to **fork the repository** first because you don't have write access. Forking it allow you to create a copy in your GitHub account of the repository at that moment.

https://github.com/eficode-academy/git-katas
# References {.unnumbered}

 - Recognize the essential components of a pull request.
              - Determine whether merging changes is preferable to opening a pull request.
              
This website's material could be used, for example, to adapt a The Carpentries lesson for the specific needs of the course you are teaching. Are you using the material to teach undergrad students with no background on computer sciences? Are you covering different ages? Are you training scientist? Are your students struggling with a particular topic and you would like to reinforce a topic with more activities but you don't have time to create new ones? On this cases I think


### Dealing with abstraction

The learning objectives x, y and z try to explore that. 

But abstraction is not only part of this when are teaching the commands. Branching for example, is another concept that can be really clarified with the help of visualizations, that are not always easy to understand and can have variations in different IDEs or suing different flags in the the commands.

The learning objectives x, y and z explore that.

### Programmers are humans!
Git is a tool that makes easier to collaborate with others. Here GitHub takes the lead with a battery of tools that support the collaborative use of Git. The same way documentation is essential for software development, these instances are relevant to communicate with others and also ensure the reproducibility of the project.

Effective use of the tools could imply good commit messages and meaningful name of branches. This has nothing to do with the tool, but will ensure the effective use of the tool.

The learning objectives x, y and z go through this.

### The victorinox

Git and GitHub have many tools. Some of them will be practical only in particular reasons. The decision among using git revert or git reset could be done in relation if you are working with colleagues or only by yourself.
Teaching the tool is affected by the use. Should the use of `git stash` be only explained as a handy tool to avoid merge conflicts? You can also use it for X.
There is not a correct answer, this will be defined in relation to the learning outcome expected as instructor but it is definetly something that should be considered in relation.
s


## Books

- Happy Git with R
 

    Ifat Neumann
    March 19, 2021

A Non-Scary Introduction to The Wondrous World of Git

- 

- Loeliger, J., & McCullough, M. (2012). Version Control with Git: Powerful tools and techniques for collaborative software development. " O'Reilly Media, Inc.".


## Articles

- [Version Control System: A Review](https://doi.org/10.1016/j.procs.2018.08.191)

- Challenges and Confusions in Learning Version Control with Git

Bryan, J. (2018). Excuse me, do you have a moment to talk about version control?. The American Statistician, 72(1), 20-27.
 @bryan2018excuse

## Communities

- The Carpentries

- Code Refinery

- The Turing Way

# References {.unnumbered}

::: {#refs}

:::
