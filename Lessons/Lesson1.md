# Lesson 1

This lesson covers the following topics:

- Discuss required tools
- Section 1.1 – Create New Project
    - Create a new project
    - Create a python environment
    - Create and run your first hello world project in python. 

## Required Tools 

- Install Python – Download python 3.11 from https://www.python.org/downloads/release/python-31110/
- Install VSCode (optional) – Download from https://code.visualstudio.com/ 
- Install Git (optional) – For Windows download Git for Windows from  https://gitforwindows.org/ 
- Install Docker (optional) – Download Docker Desktop from https://www.docker.com/products/docker-desktop 
- Create Account on Github (optional) – Useful for shared projects through this training 

## Training – Section 1.1 – Create New Project

Open your command prompt or terminal to create a new folder for your project. 
```bash
# Create a `src` folder somewhere on your computer 
mkdir src

# Create a new Folder under `src` called `training` 
mkdir src/training

# Navigate to folder
cd /path/to/src/training

# Create new python environment 
python -m venv .venv 

# Activate the new environment 
source ./venv/Scripts/activate

# Open VSCode 
code .
```

Create a new file called `main.py` in your project with the following content.

```python
#!/usr/bin/python 

if __name__ == "__main__": 

    print("hello world") 
```

Run your file from the command line 

```bash
$(.venv)path/to/src/training>python main.py 
```

## Training – Section 1.2 – Run Dev Project

```bash
# Install flake8 and black 
python -m pip install flake8
python -m pip install black

# Run flake8
flake8 main.py

# Run black
black main.py
```
