# Simple Calculator Project

This is a simple calculator project that demonstrates GitHub Actions in action. The project includes:

- A basic calculator module with arithmetic operations
- Unit tests
- GitHub Actions workflow for continuous integration

## Features

- Basic arithmetic operations (add, subtract, multiply, divide)
- Unit tests with pytest
- Code coverage reporting
- Linting with flake8
- GitHub Actions workflow

## Setup

1. Clone the repository
2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Running Tests

To run the tests locally:
```bash
pytest test_calculator.py -v
```

## GitHub Actions

The project includes a GitHub Actions workflow that:
- Runs on push to main branch and pull requests
- Sets up Python 3.10
- Installs dependencies
- Runs tests with coverage
- Performs linting

To see the workflow in action:
1. Push changes to the repository
2. Create a pull request
3. Check the Actions tab in GitHub 