# langscratch - Misc things with LangChain

## Python set up

To avoid any issues with WSL, Ubuntu, and Python here's the set up using uv

1. Create the virtual environment like this: `uv venv --python 3.12`
2. Activate the virtual environment: `source .venv/bin/activate`
3. Install the requirements: `uv pip install -r requirements.txt`
4. Optionally to pin the version of the packages, run: `uv pip freeze > requirements.txt`
5. Run jupyter in a self contained environment via `uv run --with jupyter jupyter notebook`

## Notebooks

* langchain-setup-check.ipynb - A notebook to check if the LangChain setup is working correctly.