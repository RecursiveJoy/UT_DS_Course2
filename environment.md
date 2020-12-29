# Data Science Environment Setup for Course 2
---
tags: ( #environment, #anaconda )
date updated: 12-28-20 for #course_2

---
**Windows 10:**

1. install anaconda, do not install into a dir with spaces in the name, do not add to path, set as default python, chose python 3.8.
2. the DS_DA course files (jupyter notebook file and data files) are stored in their respective course folders inside a folder called DS_DA which is stored in ~
3. Use the anaconda navigator to install the conda powershell prompt & run it from the start menu. pin to taskbar.
4. conda install jupyter notebook.
5. conda install pandas (data analysis)
6. conda install numpy (already installed by default.)
7. conda install scikit-learn (machine learning)
8. conda install seaborn (data visualization library)
9. conda install statsmodels (for multiple regression)
10. conda install sqlalchemy (for sql)
11. conda install pymysql (for mysql)
12. conda install -c conda-forge pandas-profiling

---
Git Setup
---
1. conda install git from your preferred virtual environment
2. configure git for the first time
```
\$ git config --global user.name "John Doe"
\$ git config --global user.email johndoe@example.com
\$ git config --global core.editor atom
\$ git config --global init.defaultBranch main
```
3.
if you want to clone from an existing github repo,
    git clone URL target\_directory\_name
else
    cd into your project directory path
    type ‘git init’

4. git add -u //adds all untracked files
5. git commit -m "message" //gets the updated files ready for upload (puts in staging area)

---
# Resources
---
[Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)

---
# Resources:
---
1. [Introduction to Anaconda by Yale](https://research.computing.yale.edu/sites/default/files/files/anaconda.pdf)
2. [Conda Cheat Sheet](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf)