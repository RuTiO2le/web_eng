## Setup
```
pip install -r requirements.txt
python
```
Execute the following in interactive mode.
```python
from app import app, db

with app.app_context():
    db.create_all()
```
Then, run thins.
```
python app.py
```