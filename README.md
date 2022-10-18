# url_shortener_api

A simple API following Real Python
Tutorial (https://realpython.com/lessons/url-shortener-fastapi-overview/) for
building a URL shortener.<br>
This project uses FastAPI and SQLAchemy as framework and ORM and uvicorn as
server.<br>
<br>

To run this project do:

* Create a Python virtual enviorment

```shell
python3 -m venv venv
```

* Install dependencies with

```shell
python3 -m pip install -r requirements.txt
```

* Create a ```.env``` file with your variables as follows

```dotenv
ENV_NAME="Development"
BASE_URL="http://127.0.0.1:8000"
DB_URL="sqlite:///./shortener.db"
```

* Run the server

```shell
uvicorn shortener_app.main:app --reload 
```