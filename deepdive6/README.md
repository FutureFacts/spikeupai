# Data Science Deep dive 6

## Gettings started
Installing a virtual environment:

- clone the repository
- navigate to the deepdive6 folder in the terminal/powershell: `cd deepdive6`
- create a new pyhton virtual environment
    - Check if you want to make a python venv with the current python executable:
        - what is you python version?: `python --version`
        - where is your python installed? 
            - start python shell: `python`
            - `import sys`
            - `sys.executable`
    - create virtual environment: `python -m venv .venv`
    - activate virtual environment: `.\.venv\Scripts\activate`
- install requirements:
    - `pip install -r requirements.txt`
- make your virtual environment available as a jupyter notebook kernel: `ipython kernel install --user --name=deepdive6`
    - if it doesn't show up in VSCode restart.