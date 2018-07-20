## programming-exercises/flask

## Exercises
* [hello](hello) - Flask hello world
  * `pip install flask'
  * `export FLASK_APP=hello.py`
  * `flask run`
* [flask-tutorial](flask-tutorial) - Flask tutorial
  * Create `flaskr/__init__.py`
  * `export FLASK_APP=flaskr`
  * `export FLASK_ENV=development`
  * Create `flaskr/db.py`
  * Create `flaskr/schema.sql`
  * `flask init-db`
  * Create `flaskr/auth.py`
  * Create `flaskr/templates/base.html`
  * Create `flaskr/templates/auth/register.html` and `login.html`
  * Create `flaskr/static/style.css`
  * Create `flaskr/blog.py`
  * Create `flaskr/templates/blog/index.html`, `create.html` and `update.html`
  * Create `setup.py` and `MANIFEST.in`
  * `pip install -e .`
  * `pip list`
  * Keep the package for running pytest, otherwise can do `pip uninstall flaskr`
  * `pip install pytest coverage`
  * Create `tests/*`
  * Create `setup.cfg`
  * Run `pytest` under flask-tutorial
  * Run `coverage run -m pytest` followed by `coverage report` or `coverage html`

## References
* Flask Tutorial
  * http://flask.pocoo.org/docs/1.0/tutorial/

