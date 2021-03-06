# Talos QA RobotFramwork Training
# Project Setup

## Requirements
1. **Git** 
2. **Python 3.6+** 
3. **Robot**
4. **pip**
5. chromedriver
6. Selenium Library

> If you don't have homebrew installed go to [Homebrew installation](#homebrew-installation)

Before starting the installlation process, check what is already installed with the following comands:
- `git version`
- `python --version` in case you have more than one python version installed use `python3 --version`
- `robot --version`
- `pip --version`  in case you have more than one pip version installed use `pip3 -- version`
- `chromedriver --version`


### Git Installation
1. Open your **Terminal** app (Quit it first if already open)
2. Run the following command `brew install git`
3. Verify your installation with `git version`

### Python and pip installation
1. Open your **Terminal** app (Quit it first if already open)
2. Run the following command `brew install python3`
3. Verify your python installation with `python --version` if you have more than one python version installed use `python3 --version`
4. Verify pip was installed with `pip --version`  if you have more than one pip version installed use `pip3 -- version`

### Robot Installation
*If you have more than 1 pip versione installed do all the following comands with pip3 instead if pip*

1. Open your **Terminal** app (Quit it first if already open)
2. Run the following command `pip install robotframework`
3. Verify robot was installed running the following command `robot --version`

### Selenium Library
*If you have more than 1 pip versione installed do all the following comands with pip3 instead if pip*

1. Open your **Terminal** app (Quit it first if already open)
2. Run the following command ` pip install --upgrade robotframework-seleniumlibrary`
3. Verify selenium library was installed running the folloeing command `pip show robotframework-seleniumlibrary`

## Chrome and Firefox(this one is optional) Driver Installation
*If you have more than 1 pip versione installed do all the following comands with pip3 instead if pip*

1. Open your **Terminal** app (Quit it first if already open)
2. Run the following command `pip install webdrivermanager`
3. Run the following command `webdrivermanager firefox chrome --linkpath /usr/local/bin`
4. Verify the driver(s) was/were installed with the following comand Chrome: `chromedriver --version`   Firefox: `geckodriver --version`

### Homebrew Installation 
1. Open your **Terminal** app (Quit it first if already open)
2. Run the following comand  `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
3. Follow the steps that are shown in the **Terminal** window
4. Verify your installation with `brew --version`
