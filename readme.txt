# ===============================================
The Zen of Python
Written by: Kevin Hallquist, WB7BGJ

This simple Flash application provides a single URL route that
returns an HTML page containing the aphorisms of the well
known Easter Egg in Python called "import this"

# ===============================================
To setup the needed Python virtual environment for this application
open a command prompt in the folder where you put the project files
and use the following commands:
    
	1. This creates a new Python virtual environment for the project
	> python -m venv .venv
		
    2. This activates the virtual environment for use by the project
	> .venv\Scripts\activate.bat
	
	3. This installs the required modules for the project in the virtual environment 
	> pip install -r requirements.txt

# ===============================================
To run this application from the command prompt type:
	> python .\The_Zen_of_Python.py

The following text should be displayed:
    * Serving Flask app 'the_zen_of_python' (lazy loading)
    * Environment: production
    WARNING: This is a development server. Do not use it in a production deployment.
    Use a production WSGI server instead.
    * Debug mode: off
    * Running on http://127.0.0.1:3000 (Press CTRL+C to quit)

# ===============================================
To view the home web page of this application, open a web browser 
and type the following URL: http://127.0.0.1:3000/