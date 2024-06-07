# datafun-07-ml
This project will create a supervised machine learning program to create a linear regression equation to make predictions on datasets. 
## Create Project Virtual Environment and update pip and install requests

On mac, create a project virtual environment in the .venv folder. 

''' zsh
python3 -m venv .venv
cd documents/data_analytics/datafun-04-jupyter/.venv/bin
source activate
touch requirements.txt
python3 -m pip install -r requirements.txt
python3 -m pip install jupyterlab numpy pandas matplotlib seaborn scipy scitkit-learn
python3 -m pip freeze > requirements.txt
touch .gitignore
'''
add lines .venv/, .vscode/, and .ipynb_checkpoints/ to .gitignore file

## Git add and commit

'''zsh
git add .
git commit -m "add .gitignore, cmds to readme"
git push origin main
'''

