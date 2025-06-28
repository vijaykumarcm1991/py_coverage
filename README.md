# Run Automated Tests in GitHub Actions
## Objective
Set up automated testing in GitHub Actions using pytest.

## Tasks
**Task 1**: Create a Python Test File
Write a simple Python function (e.g., a calculator function).
Create a pytest test file (test_script.py) to verify its correctness.

Example function (script.py):
```
def add(a, b):
    return a + b
```
Example test file (test_script.py):

```
from script import add

def test_add():
    assert add(2, 3) == 5
```

**Task 2:** Configure GitHub Actions for Automated Testing
Create a .github/workflows/test.yml file.
Set up a GitHub Actions workflow that:
Installs dependencies (pytest).
Runs the tests automatically on every push and pull request.

**Bonus Task**
Extend the workflow to generate a code coverage report using pytest-cov.

**Expected Outcome**
The workflow should trigger automatically on every push and pull request.
The tests should run successfully in the GitHub Actions environment.
If any test fails, the workflow should return an error status.
The bonus task should generate a code coverage report to analyze test coverage.
