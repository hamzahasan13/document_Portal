# Project Setup Guide

### Create a new project folder
```
mkdir <project_folder_name>
```
### Move into the project folder
```
cd <project_folder_name>
```
### Open the folder in VS Code
```
code .
```
### Create a new Conda environment with Python 3.10
```
conda create -p <env_name> python=3.10 -y
touch .env
```

### Activate the environment (use full path to the environment)
```
conda activate <path_of_the_env>
```

### Install dependencies from requirements.txt
```
pip install -r requirements.txt
```

### Initialize Git
```
git init
```

### Stage all files
```
git add .
```

### Commit changes
```
git commit -m "<write your commit message>"
```

### Push to remote (after adding remote origin)
```
git push
```

### Cloning the repository
```
git clone <>
```

### Setup
```
touch setup.py
```

### Logging & Exception
```
mkdir logger
touch logger/custom_logger.py
```
```
mkdir exception
touch exception/custom_exception.py
```

### Source Code
```
mkdir src
```
### Utils
```
mkdir utils
```

### Experiments
```
mkdir notebook
```
```
touch notebook/experiments.ipynb
```

### Config
```
mkdir config
```
```
touch config/config.yaml
```

### Prompts
```
mkdir prompt
touch prompt/prompt_library.py
```

### Main App
```
touch app.py
```
### Templates
```
mkdir templates
touch templates/index.html
```

### Static
```
mkdir static
touch static/style.css
```
### Initializing Setup.py
```
pip install -e .
```