Open Command Prompt, make sure you have the project directory selected, 
you can do this with the command cd c:\your_project_folder_destination on Windows.
set FLASK_APP=main.py
set FLASK_DEBUG=1
flask run



For pycharm windows run these line on the terminal:
set FLASK_APP=main.py
$env:FLASK_APP = "main.py"
set FLASK_DEBUG=1
flask run