# Lesson 1

This lesson guides you through setting up your environment and creating your first hello world project in python. 

## Install Tools 

- Install Python – Download python 3.11 from https://www.python.org/downloads/release/python-31110/
- Install VSCode (optional) – Download from https://code.visualstudio.com/ 
- Install Git (optional) – For Windows download Git for Windows from  https://gitforwindows.org/ 
- Install Docker (optional) – Download Docker Desktop from https://www.docker.com/products/docker-desktop 
- Create Account on Github (optional) – Useful for shared projects through this training 

## Create Your Project

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
