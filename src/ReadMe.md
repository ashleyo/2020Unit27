0. Prerequsities: VisualStudio Code, Python >=3.6

1. Clone the repo locally

2. In the root folder of the project (the one you cloned to) create a virtual env, I use `python -m venv env`

3. Activate the env, in VSC Shift-Ctrl-P and 'Select Python Interpreter' to be the one with 'env' in the name, now Shift-Ctrl-' to launch a shell in that environment (should see 'env' as part of the prompt)

4. `cd src`

5. `pip install -r requirements.txt`

6. `cd wikisite`

7. `python manage.py migrate`

8. `python manage.py createsuperuser`

9. `python manage.py check` should report no problems
