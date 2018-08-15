# A basic poll application

A Django basic poll application from the [Django Tutorials](https://docs.djangoproject.com/en/2.1/intro/tutorial01/)

It’ll consist of two parts:

* A public site that lets people view polls and vote in them.
* An admin site that lets you add, change, and delete polls.

# Setting up your system

Make sure you already have Python3, Pip and Virtualenv installed in your system.

# How to get started

Start by making a directory where we will work on. Simply Open your terminal and then:

```
mkdir basic_poll_application
```

Afterwhich we go into the directory:

```
cd basic_poll_application
```

## Create a Python Virtual Environment for our Project

Since we are using Python 3, create a virtual environment by typing:

```
virtualenv -p python3 .
```

Before we install our project's Python requirements, we need to activate the virtual environment. You can do that by typing:

```
source bin/activate
```

## Clone and Configure a New Django Project

Login into your github account and open the project folder then follow the instruction on how to clone the existing project. It should be something similar to:

```
git clone https://github.com/<your_github_username>/basic-poll-application.git 
```

Next, install the requirements by typing:

```
pip install -r requirements.txt
```

