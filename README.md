                                  In this repository, we will cover step by step installation of 1st Python Project using FastApi & Uvicorn in babysteps.

Step 1: Install pipx.
	a - Make a folder on your desktop or whatever you wanted(Desktop Recommnended).
  b - Open your terminal by entering (code .) in the navigation of the selected folder.
	c - Install pipx using this pip command : `python -m pip install --user pipx`

Step 2: Ensure pipx's binary directory is in your PATH: `python -m pipx ensurepath`. This is not compulsory step.

Step 3: Restart your terminal to apply the PATH update.

Step 4: run the command `pipx install poetry`. Most important command.

Step 5: To check the version run `poetry --version`. only to verify that poetry is installed or not. 

Step 6: Create a new project with `poetry new uit-api-class --name uitclass`. (Name of the project/folder) that you already made. 

Step 7: open the sub folder inside of the parent folder, in this case `uitclass`

Step 8: Now create a new file named `main.py` in uitclass.

Step 9 (optional): Check the version of python with the command `poetry run python --version`

Step 10: poetry add fastapi uvicorn.

Step 10a (optional): Check the packages inside of the pyproject.toml

Step 11: Write the hello world code in the main.py file:
	
Step 12: run the server: uvicorn (mean server) run main(file name):app(from where we want to get) and (--reload) to make it reloadable
Example: uvicorn main:app --reload 

Step 13: Enter the commnad `Poetry shell`
it will make a virtual environment and might be in green color. Copy that path.

Step 14: Enter the shortcut on you PC
a) if Windows: Ctrl+Shift+P
b) if Mac: Cmmnd+Shift+P
  Then a terminal open. 
  Type Python Interpretor.
  Select Python interpretor.
  Click on Enter Path.
  Then paste the copied path. 
  It will create a local server 
	- http://0.0.0.0:8000/
	or 
	- http://localhost:8000 and here you go
If you made any kind of change please reload the page.

 
 
