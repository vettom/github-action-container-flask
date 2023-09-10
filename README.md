# Task in hand

## Build and deploy python flask app to container

# CI Tasks
- Up on pull
  - pylint
  - test app
  - build container
  - upload to repo


# Generate requirement.txt
```bash
python -m venv venv
source venv/bin/activate
pip install flask
pip freeze > requirements.txt
deactivate
```

