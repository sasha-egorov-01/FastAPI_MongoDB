# MongoDB with FastAPI

This is a small sample project demonstrating how to build an API with [MongoDB](https://developer.mongodb.com/) and [FastAPI](https://fastapi.tiangolo.com/).
It was written to accompany a [blog post](https://developer.mongodb.com/quickstart/python-quickstart-fastapi/) - you should go read it!


If you really don't want to read the [blog post](https://developer.mongodb.com/quickstart/python-quickstart-fastapi/) and want to get up and running,
activate your Python virtualenv, and then run the following from your terminal (edit the `DB_URL` first!):

```bash
# Install the requirements:
pip install -r requirements.txt

# Start the service:
uvicorn app:app --reload
```

(Check out [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) if you need a MongoDB database.)

Now you can load http://localhost:8000 in your browser ... but there won't be much to see until you've inserted some data.
