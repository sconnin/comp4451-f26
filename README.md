

## Student: setup UV Project for Comp4451

1. Install uv & git 

2. Clone the Github repository:

    git clone https://github.com/sconnin/comp4451-f26.git

3. Change into the project directory:

    cd comp4451-f26

4. Install dependencies

    uv sync # the environment is updated automatically; reads pyproject.toml and uv.lock (exact package versions)

5. Run the application

    uv run python main.py

### Updates

6. To update with additional packages that I add during the course - you will be notified first

    git pull 
    uv sync 

### VSCODE

7. Select the Python Interpreter named for the repository (comp4451-f26)