# SETUP

1. Ensure Python v3.8.9 is installed (preferably with virtualenv)

2. Run `virtualenv venv` or `python3 -m venv venv`

3. To activate virtual environment, run `./venv/bin/activate.ps1` for pwsh (powershell) console

4. Run `pip install -r requirements.txt` to install all dependencies.

# INSTALLING DEPENDENCIES

1. `pip install` new dependency, then run `pip freeze > requirements.txt` to save dependency list to requirements file.