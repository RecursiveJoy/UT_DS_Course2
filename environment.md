# Data Science Environment Setup for Course 2
---
tags: ( #environment, #anaconda )
date updated: 12-28-20 for #course_2

---
## Environment Setup for Windows
---
### installing git and Anaconda
---

1. install anaconda, do not install into a dir with spaces in the name, do not add to path, set as default python, chose python 3.8. If you install conda into the ~ directory, its apps will only be available in ~ and its subdirectories.

2. conda install git from your preferred virtual environment. This will install git for the directory you installed Anaconda into. Git will only be available for that directory and its subdirectories.

3. Open the conda powershell prompt. Configure git for the first time:
```
\$ git config --global user.name "John Doe"
\$ git config --global user.email johndoe@example.com
\$ git config --global core.editor atom
\$ git config --global init.defaultBranch main
```
4. Create your local Git repo:

    a. if you want to clone from an existing github repo,
       git clone URL target\_directory\_name
    b. otherwise
        cd into your project directory path
        type ‘git init’
---
### Installing the needed IDE and libraries
---
 conda install jupyter notebook (ide)
 conda install pandas (data analysis)
 conda install numpy (already installed by default.)
 conda install scikit-learn (machine learning)
 conda install seaborn (data visualization library)
 conda install statsmodels (for multiple regression)
 conda install sqlalchemy (for sql)
 conda install pymysql (for mysql)
 conda install -c conda-forge pandas-profiling

---
# Resources
---
1. [Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)

2. [Introduction to Anaconda by Yale](https://research.computing.yale.edu/sites/default/files/files/anaconda.pdf)
3. [Conda Cheat Sheet](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf)

4. [Git Immersion](https://gitimmersion.com/)

5. [Pro Git book](https://git-scm.com/book/en/v2)
