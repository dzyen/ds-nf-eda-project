[![Shipping files](https://github.com/neuefische/ds-eda-project-template/actions/workflows/workflow-03.yml/badge.svg?branch=main&event=workflow_dispatch)](https://github.com/neuefische/ds-eda-project-template/actions/workflows/workflow-03.yml)
# EDA Project (September 2025)
As part of the Data Science Bootcamp at neue fische.
This project focuses on Exploratory Data Analysis using a King County housing database, containing information about property and home sales in King County (USA). 


# Tasks
* Define 3 hypothesis that can be proven using the provided data.
* Come up with recommendations for a chosen client.

## Hypothesis to test
- Houses that are 5km away from the center of Seattle are 20% cheaper than houses inside a 5km radius from the center.
- The most expensive 25% of houses are in zip codes that have at least one golf course.
- Houses that meet the clients conditions are in the top 25% of house prices.
- Houses within the same zipcode are build within 50 years from each other.

## Client conditions
Role: Buyer\
Characteristics:\
Unlimited budget.
Wants either:\
– Big lot (tennis court, pool), 4+ bathrooms, golf, historic.\
– Or smaller house nearby.
No waterfront.


# Requirements

- pyenv
- python==3.11.3

## Set up your Environment
This repo contains a requirements.txt file with a list of all the packages and dependencies you will need.

Before you can start with plotly in Jupyter Lab you have to install node.js (if you haven't done it before).
- Check **Node version**  by run the following commands:
    ```sh
    node -v
    ```
    If you haven't installed it yet, begin at `step_1`. Otherwise, proceed to `step_2`.


### **`macOS`** type the following commands : 


- `Step_1:` Update Homebrew and install Node by following commands:
    ```sh
    brew update
    brew install node
    ```

- `Step_2:` Install the virtual environment and the required packages by following commands:

    ```BASH
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/bin/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```
### **`WindowsOS`** type the following commands :


- `Step_1:` Update Chocolatey and install Node by following commands:
    ```sh
    choco upgrade chocolatey
    choco install nodejs
    ```

- `Step_2:` Install the virtual environment and the required packages by following commands.

   For `PowerShell` CLI :

    ```PowerShell
    pyenv local 3.11.3
    python -m venv .venv
    .venv\Scripts\Activate.ps1
    python -m pip install --upgrade pip
    pip install -r requirements.txt
    ```

    For `Git-Bash` CLI :
  
    ```BASH
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/Scripts/activate
    python -m pip install --upgrade pip
    pip install -r requirements.txt
    ```
    
# Collaborators of this project:
Dizzy Englmaier\
Chavely Albert Fernandez\

# Contents of the repository
* Database in data/eda.csv
* EDA.ipynb Notebook containing the created code to perform the tasks
* Image folder with images created as part of the project
* requirements.txt file with a list of all the packages and dependencies you will need.
  

