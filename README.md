# 80 Points

A trick-based game where teams of players earn points to advance their levels.

## Setup 

```bash
# Creates a directory to hold dependencies
python3 -m venv venv

# Activate the virtual environment
source venv/bin/activate

# Install Python dependencies needed
pip install -r requirements.txt
```

## Run the server

```bash
python3 server/server.py
```

## Run unit tests (must be run under server/ directory)

```bash
# Run a single test
python3 -m unittest model_test.py

# Runs all tests
python3 -m unittest *_test.py
```