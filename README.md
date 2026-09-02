

## Student: setup UV Project for Comp4451

1. Install uv & git 

2. Clone the Github repository:

    git clone <repo-url>

3. Change into the project directory:

    cd comp4451-f26

4. Install dependencies

    uv sync # the environment is updated automatically; reads pyproject.toml and uv.lock (exact package versions)

5. Run the application

    uv run python main.py

### Updates

6. To update with additional packages that I add

    git pull 
    uv sync 
