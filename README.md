# SlapThatLikeButton-TestingStarterProject
A starter project to show how to set up and use automated testing in Python

![Tests](https://github.com/mCodingLLC/SlapThatLikeButton-TestingStarterProject/actions/workflows/tests.yml/badge.svg)

# RBH Notes

`pytest` for running tests

`mypy` for checking type hints

`flake8` for linting / checking code style

`tox` for running in all different environments

`GhutHub Actions` for running tox and all test every time we push to repo

From project root, install package (editable-mode/symbolic-link) and dependencies (requirements.txt) ...
```commandline
pip install -e .
```

Result ...
```text
Obtaining file:///Users/rbhana/from-git/learning/mCodingLLC-SlapThatLikeButton-TestingStarterProject
  Installing build dependencies ... done
  Checking if build backend supports build_editable ... done
  Getting requirements to build wheel ... done
  Preparing metadata (pyproject.toml) ... done
Requirement already satisfied: requests>=2 in ./venv/lib/python3.10/site-packages (from slapping==0.0.0) (2.26.0)
Requirement already satisfied: urllib3<1.27,>=1.21.1 in ./venv/lib/python3.10/site-packages (from requests>=2->slapping==0.0.0) (1.26.9)
Requirement already satisfied: certifi>=2017.4.17 in ./venv/lib/python3.10/site-packages (from requests>=2->slapping==0.0.0) (2022.5.18.1)
Requirement already satisfied: idna<4,>=2.5 in ./venv/lib/python3.10/site-packages (from requests>=2->slapping==0.0.0) (3.3)
Requirement already satisfied: charset-normalizer~=2.0.0 in ./venv/lib/python3.10/site-packages (from requests>=2->slapping==0.0.0) (2.0.12)
Installing collected packages: slapping
  Running setup.py develop for slapping
Successfully installed slapping-0.0.0
```