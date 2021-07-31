---
layout: default
title: Setup Virtual Environment
parent: Getting Started
nav_order: 1
description: "Setup Virtual Environment and install necessary Python libraries."
has_children: false
permalink: /getting_started/setup_virtual_environment/
has_toc: false
---

# Setup Instructions
- Clone Repo from GitHub
- **Setup Virtual Environment**
- Run Data Pipeline

# Setup Environment
Next, you'll need to setup a virtual environment. In command line, we'll create a new virtual environment called *env*:
```
pip install --upgrade pip
pip install virtualenv
python -m venv env
```

Now you should see a directory called *env* in your project directory, and now we can activate the environment:
```
. env/bin/activate
```

Each time you're done working on the project, you can deactivate the virtual environment by using the `deaactivate` command.

We'll now install the Python libraries we need into *env*. A list of the once we need are located in *requirements.txt*, and we'll use that information for the installation:
```
pip install -r requirements.txt --upgrade
```
