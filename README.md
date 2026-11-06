# Flask Blog

A blog built with Flask and SQLite: create, view, edit and delete posts.

## Run

```bash
python -m venv venv
source venv/bin/activate      # Windows: venv\Scripts\activate
pip install -r requirements.txt
python init_db.py             # creates database.db with sample posts
python app.py                 # then open http://127.0.0.1:5000
```
