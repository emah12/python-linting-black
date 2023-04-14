# python-linting-black

## packages
- black
- safety
- pip-audit

## instructions
- https://black.readthedocs.io/en/stable/usage_and_configuration/the_basics.html

## simple BLACK tutorial
- Install: 'pip install black'
- We have 1: poorly linted Python file called 'poorPythonfile.py'
- In order to run, we then need to call 'black' or 'python black' from the terminal command line 
- If we want to do directory, ./select the directory
- If we want to see changes, add the argument '--diff' to the end
    - Ex: 'black ./directory --diff'

## simple SAFETY tutorial
- Install: 'pip install safety'
- Test: 'safety check --key <your_api_key>'
- Look at a specific requirements.txt file
    - 'safety check -r <path-to-requirements-file> --key <YOUR-API-KEY>'
    - Ex: 'safety check -r ./directory/requirements.txt --key <YOUR-API-KEY>'
- Saving output:
    - v1: 'safety check -r <YOUR-REQUIREMENTS.TXT> --key <YOUR-API-KEY> --output screen > securityCheck.txt'
    - v2: 'safety check -r <YOUR-REQUIREMENTS.TXT> --key <YOUR-API-KEY> --output json > securityCheck.json'
