# DESCRIPTION

This project is created to show how e2e testing of https://www.automationexercise.com can be organized with Playwright framework using Python, POM (Page Object Model)

## REQUIREMENTS:

 - Python
 - Pip

### INSTALLATION:
 -  Clone repository
```
git clone https://github.com/MaxixV2/pytest_task.git
```
 - Install environment
```
python -m pip install --upgrade pip
pip install pipenv
pipenv install --system
playwright install chromium
```
### Usage:
## Tests
To run tests use:
```
pytest
```
To run specific spec file use:
```
pytest -k <test_file_name>
```
## Reports
To view auto generated reports run
```
allure serve reports
```

Example of Allure report

![image](https://github.com/MaxixV2/pytest_task/assets/99399536/f0e6fd83-0dba-41ed-84eb-bfac9cdacdac)
