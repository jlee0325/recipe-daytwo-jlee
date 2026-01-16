# recipe-daytwo-jlee


## Step-by-step recipe
### 1. Create/open a project folder (or clone a repo) and open it in VS Code.
### 2. Open a terminal in the project root and confirm location with `pwd` / `ls`.
### 3. Create a virtual environment: `python3 -m venv .venv`
### 4. Activate the environment: `source .venv/bin/activate`
### 5. Upgrade pip: `python -m pip install --upgrade pip`
### 6. Install needed packages (example): `python -m pip install ipykernel pandas plotly`
### 7. Create/update `requirements.txt`: `python -m pip freeze > requirements.txt`
### 8. Add the venv to `.gitignore` so it isn’t committed: add `.venv/`
### 9. Quick test run (optional): `python -c "import pandas, plotly; print('ok')"`
### 10. Commit + push your changes.

## Creating a new working project environment using these steps
### Commands used (example):
### ```bash
### mkdir -p new_project_env
### cd new_project_env
### python3 -m venv .venv
### source .venv/bin/activate
### python -m pip install --upgrade pip
### python -m pip install ipykernel pandas plotly
### python -m pip freeze > requirements.txt
### python -c "import pandas, plotly; print('ok')"
### ```
