# Yelp Data Pipeline

Minimal data pipeline implemented using Apache Spark to extract and transform the data.

# Source Data
https://www.yelp.com/dataset

Download the zip file and extract it under `ydp/data/yelp`

# Setup

```bash
# Install pipenv
pip install pipenv
# Create virtual environment
pipenv install
# Start the shell
pipenv shell
# Copy virtual environment name by using the location printed after launching the shell
# . /Users/user/.local/share/virtualenvs/my-venv-name/bin/activate
# Create a kernel for the jupyter notebook to use virtual environment
pipenv install ipykernel
python -m ipykernel install --user --name=my-venv-name
# Start jupyter notebook
jupyter notebook
# Set the kernel to my-venv-name by going to the notebook -> Kernel -> Change Kernel -> my-venv-name
```