# hypermedia

A Hypermedia example from https://hypermedia.systems/book/a-web-1-0-application/

Code from: https://github.com/bigskysoftware/contact-app

**Activate the virtual env and install requirements from requirements.txt:**
```
python -m venv env
.\env\Scripts\Activate.ps1
pip install Flask
pip install -r requirements.txt
```

**Run the app locally:**
```
.\env\Scripts\Activate.ps1
$env:FLASK_APP = "app.py"
flask run
```