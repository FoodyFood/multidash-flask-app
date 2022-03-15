# MultiDash Flask App

Flask app that has a mix of both embedded Dash apps and pure html pages.

This multidash flask app will run inside JupyterHub and allow external viewing by leveraging Jupyter Proxy.

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
```

### Run MultiDash Flask App

```bash
make run # Assumes you have activated the venv and installed as above
```

### View Externally

With the url_prefix set to the string used for external browsing, you can view the dash here:

https://example.com/user/{username}/proxy/{port}/

Example using the values in main:
https://example.com/user/user@example.com/proxy/8050/
