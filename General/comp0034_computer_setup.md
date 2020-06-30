# Software, tools and code libraries used in the course
The following list is subject to change and is exhaustive list. It should however provide you with a good starting point for the course.

## What to do if you don't have access to a computer
Most students will prefer to install software to use on their own computer. However, you may be in a position where this is not possible.   
As far as is possible, online alternatives to using your own computer have been indicated.  
If you do not have access to a computer on which you can install software, and have difficulty in completing any of the course using the online alternatives suggested, then please email me, <sarah.sanders@ucl.ac.uk> (course tutor), so that I am aware of your constraint.

## Checklist of what you will need
- [ ] A code editing environment for Python, SQL, CSS, HTML and JavaScript
- [ ] Source code control
- [ ] Web app framework (Flask)
- [ ] Database (SQLite)
- [ ] Data set

## Installation
You will be asked to install (if using software installed directly on your computer), or establish access to (if working online), at least one software or service for each item on the checklist above.

You do not need to install all of the following in week 1, you will be directed when and how to install, or gain access to, each element.1

This document is provided as a resouce that you can refer to at any time during the course.

### 1. Python 3
If you are using your own computer and developing files locally (i.e. not using an online code editor) then you will need to install [Python 3.5 (or newer)](https://www.python.org/downloads/).
If you are using an online code editors only then skip to section 2.1.

### 2. Code editor
You will need a way to edit Python, Flask (python, Jinja2), SQL, HTML, CSS and JavaScript code.  
The most powerful way to edit code is to use an integrated development environment (IDE). IDEs features that go beyond simple code writing to make a developer's life easier. However, they do take some time to learn how to use, and if you are installing on your own computer they can require a significant amount of disk space.
There are many IDEs that are freely available to students and can be downloaded and installed. The following are some of the most popular for Python.
- PyCharm Professional ([apply for free student license](https://www.jetbrains.com/community/education/#students))
- [Visual Studio Code](https://code.visualstudio.com/download) (free)
- [Atom](https://atom.io) (free)

If you already have a preferred IDE or editor that supports Python, Flask (python, Jinja2), SQL, HTML, CSS and JavaScript then feel free to continue using it.

**The course tutor will use PyCharm Professional in class and video materials.**

### 2.1 Online code editors
There are a number of online code editors that you may be able to use. You may need to use different editors for different activities.
- [Codeshare](https://codeshare.io) Free, supports all languages  
- [Codepen](https://codepen.io) Free but only supports HTML, CSS & JavaScript (not Flask)  
- [Visual Studio Code](https://visualstudio.microsoft.com/services/visual-studio-codespaces/) Requires an Azure subscription, however they ofer $100 credit for students  
- [Gitpod](https://www.gitpod.io/pricing/) 50 hours a month free

You may also be able to complete some activities using a Jupyter notebook environment linked to your GitHub repository such as:  
- [Binder](https://mybinder.org) Free, no account required, no ability to save files.
- [AzureNotebooks](https://notebooks.azure.com) Free, account required to save files.

### 3. Source code control (using Git and GitHub)
This provides a way for you to store your code, share it with others and track changes made. While there are alternative source code control systems, you need to use GitHub for this course. GitHub is an online service for managing code that uses the Git version control software.
You should follow 3.1 if you are using online tools only.
#### 3.1 GitHub
[Create a student account using your *UCL student ID*](https://education.github.com/pack). It is important that you do this as the coursework relies on your use of a UCL account.
#### 3.2 Git
If you are developing on your own computer you will also need to [install Git](https://git-scm.com/downloads). This is the underlying source code control software that GitHub uses.

### 4. 3rd party packages, modules and libraries
The following will be used in the next course, and you may need to use them to some extent in this course.

#### Web app framework
- [Flask](https://flask.palletsprojects.com/en/1.1.x/installation/#installation): a micro-framework for developing web applications in Python

You will typically install this in the Python virtual environment. There will be different ways to do this depending on the code editor you are using. A common method is to use a terminal in the virtual environment for the project and install using pip:

```python
pip install flask
```

#### Data science
- [Pandas](https://pandas.pydata.org): data analysis with Python
- [Numpy](https://numpy.org/install/): numeric library that serves as the foundation for all calculations in Python
- [Sckikit-learn](https://scikit-learn.org/stable/install.html): popular Python machine learning library (except deep learning)
- [Dash](https://dash.plotly.com/installation) and [Plotly Express](plotly express): interactive data visualisation  

Other libraries you may wish to explore:  
- [matplotlib](https://matplotlib.org)
- [seaborn](https://seaborn.pydata.org)
- [Chart.js](https://www.chartjs.org)
- [D3.js](https://d3js.org)

The installation methods for each of these may vary depending on the code editor or IDE you are using, though as for the flask framework, most or all of these can be installed using the ```pip install [software name]``` method. Installation information shoudl be available in the documentation for each package as listed above.

### Testing, Continuous Integration (CI) and Continuous Deployment (CD)
#### Testing
- [Unittest](https://docs.python.org/3/library/unittest.html) - this is part of Python3 so no further installation required.
- [Pytest](https://docs.pytest.org/en/stable/getting-started.html) - this is a python package and can be installed from the virtual environment terminal using ```pip install -U pytest```
- [Flask-Testing]() - this python package adds features to make it easier to work with unittest and pytest for Flask applications. It can be installed using ```pip install Flask-Testing```
#### Continuous Integration (CI)
This is optional, you are not required to use this for your coursework. The following are hosted services and to use each you will need to sign up for an account. Each service has its own user documentation. You do not typically need to install additional software to use these, you will instead configure a GitHub respository to use the service.
- [CircleCI](https://circleci.com)
- [GitHub Actions](https://github.com/features/actions)
- [Jenkins](https://resources.github.com/whitepapers/practical-guide-to-CI-with-Jenkins-and-GitHub/) (free with GitHub education account)
#### Continuous Deployment (CD)
This is optional, you are not required to use this for your coursework. Investigate the offers that are part of the GitHub student pack as you should find free (if limited) deployment options, or look at the free (or student) tiers of the following services:

- Heroku
- AWS

We are not covering containerisation in this course. However some of the deployment services use [Docker]().


### Data storage (database)
- [SQLite](https://www.sqlite.org/index.html) Database format that does not require a database server. The ``sqlite3``` package is included in Python 3, we will also look at other packages for accessing a database from Python.
- [DB Browser for SQLite])(https://sqlitebrowser.org/dl/) Optional. Software that allows you to create a SQLite database using a menu driven interface. Follow the instructions on the link to download and install the software.
- [MySQL Community server Optional](https://www.mysql.com/products/community/). Optional. Open source database server. You will need to download and install the software. To use MySQL requires a database server to be running. For this reason we focus on using SQLite insead of MySQL in this course. Some students however prefer to use MySQL and you are welcome to do so for the coursework.
- [Remote mysql database server](https://remotemysql.com/#about). Online MySQL server (free), and online alternative to MySQL Community Server.

Within this 10 week course we don't have the time to investigate noSQL and storage mechanisms for large data sets. You are welcome to investigate and apply these within your project if you feel you have the skills to do so.

### Data sets
Any data source that you use must comply with GDPR and UCL Computer Science ethics policy. 
Consider using a reputable source of anonymised data such as:  
- [London DataStore](https://data.london.gov.uk)
- [UK Government and local authority](https://data.gov.uk)
- [World bank open data](https://data.worldbank.org)
