# MultiDash Flask App

Flask app that has a mix of both embedded Dash apps and pure html pages.

A good reason to use flask over pure dash would be that you can add authentication and have 
other plain html paths. It's more of a conventional server in a sense. 


### Environment Setup

Bash:
```
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Windows:
```
python -m venv .venv
source .\.venv\scripts\activate
pip install -r requirements.txt