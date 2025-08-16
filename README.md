# GitHub Actions CI Starter

Minimal Python project to practice GitHub Actions CI (build & test).

## Quickstart
1) Create a new GitHub repo (empty).  
2) Download this starter, unzip, `cd` into folder.  
3) Initialize git and push:
   ```bash
   git init
   git add .
   git commit -m "init"
   git branch -M main
   git remote add origin <YOUR_REPO_URL>
   git push -u origin main
   ```
4) Check the **Actions** tab on GitHub; the CI should run automatically.

## Local run
```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
pytest -q
```