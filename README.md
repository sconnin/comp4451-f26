

## Student: setup UV Project for Comp4451

1. Install uv & git 

2. Clone the Github repository:

    git clone https://github.com/sconnin/comp4451-f26.git

3. Change into the project directory:

    cd comp4451-f26

4. Install dependencies

    uv sync # the environment is updated automatically; reads pyproject.toml and uv.lock (exact package versions)

### Terminal & VS Code script execution

5. To execute code from terminal, navigate to the folder containing your .py file and use: uv run python (python3 for macOS) <your filename>  # Note: you do not need to activate the venv when using uv run.

    Note: if you set up a uv environment without using a .toml file, you can activate the venv from terminal using:  source .venv/bin/activate (MacOS) or .venv\Scripts\activate.bat (Windows)

6. To execute VS Code (run arrow), select the Python Interpreter named for the repository (i.e., comp4451-f26). 

### Updates

7. To update with additional packages that I add during the course - you will be notified first

    git pull 
    uv sync 

### VSCODE Troubleshooting

- To open the Command Palette (Ctrl+Shift+P / Cmd+Shift+P) search for the 'Python Interpreter', select from the list as 
    appropriate. 

- If the interpreter isnt in the drop down list, hit 'Enter interpreter path' and browse to it in the project directory 
    manually. 

### Delete a cloned repository from terminal 

    rm -rf <repository name>