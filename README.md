This repo follows the [Practical Deep Learning](https://course.fast.ai/) course from fast.ai.

# Set-up
Exercises were set-up on notebooks in VS Code. Here are useful commands to set up the virtual environment.

### how virtual environment was created
```
python3 -m venv .venv
```
### activate virtual environment
```
source .venv/bin/activate
which python3
```
### deactivate virtual environment
```
deactivate
```
### list installed packages in virtual envrionment
```
python3 -m pip list
```
### install libraries in virtual environment
```
python3 -m pip install -r requirements.txt
```
### freeze installed packages to requirements.txt in virtual environment
```
python3 -m pip freeze > requirements.txt
```
# Part 1
- 1_1_creating_model_from_data.ipynb