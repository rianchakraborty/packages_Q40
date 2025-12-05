
This repository contains a minimal Python package used for demonstrating a linting pipeline with **ruff**.

## Features
- Minimal Python package structure (`src/`)
- GitHub Actions workflow
- Automatic linting with:
  - `ruff format --check`
  - `ruff check`

## CI Behavior
The pipeline fails when "bad" code is pushed.  
This demonstrates correct linting setup for the assignment.
