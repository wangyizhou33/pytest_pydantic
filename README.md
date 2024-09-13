## nice example of pytest and pydantic
[tutorial url](https://testdriven.io/blog/modern-tdd/)

One terminal  
```sh
python blog/init_db.py
FLASK_APP=blog/app.py python -m flask run
```
The other terminal
```sh
python -m pytest tests -m 'e2e'  #expect to pass
```