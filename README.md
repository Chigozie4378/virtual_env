
# Python Virtual Environment Example

This repository demonstrates how a Python virtual environment looks when set up for a project.  
It also includes a `requirements.txt` file to install the necessary libraries.

> **Note:** In real projects, the `venv` folder is usually excluded from version control using `.gitignore` and not pushed to GitHub.  
> Here, it is included only for demonstration purposes so you can see its structure.

---

## Quick Start (Mac)
### Run these commands in the code editor terminal where your project folder is opened.
This is the easier way.  

Alternatively, you can run the commands in the Mac terminal, but you must first navigate to the project directory using the `cd` command like cd /path/to/your/project

```bash
# 1. Create a virtual environment
python3 -m venv venv

# 2. Activate the virtual environment
source venv/bin/activate

# 3. Install dependencies from requirements.txt
pip install -r requirements.txt

# 4. Install a new library (example)
pip install some-library

# 5. Update requirements.txt with current installed libraries
pip freeze > requirements.txt

# 6. Generate requirements.txt for an existing project
pip freeze > requirements.txt

# 7. Deactivate the virtual environment
deactivate


