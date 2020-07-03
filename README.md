# How to create a Virtual environment in Python

Prerequites - You must have installed:

1. Install Python
2. Install Pip
3. Install VirtualEnv:  pip install virtualenv

## Windows:

Example:

1. cd C:/Users/AJIMENEZ/etl
2. virtualenv -p C:/Python3.7/python.exe .venv_etl
3. C:/Users/AJIMENEZ/etl/.venv_etl/Scripts/activate.bat
4. pip install -r requirements.txt

## Linux:

Example:

1. cd /home/ubuntu/etl
2. virtualenv -p /usr/bin/python3.5 .venv_etl
3. source .venv_etl/bin/activate
4. pip install -r requirements.txt

## Leaving the virtual environment: 
5. deactivate
