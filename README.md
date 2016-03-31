## A Simple Poll Application (Development)

This poll application is build upon famous Django official documentation. It consist of two part:
* A public site that lets people view polls and vote in them.
* An admin site that lets you add, change and delete polls.

This poll app is going to be a part of Cornstack project.

## How to setup

Create a virtualenv in your system and clone this repositories

```python
git clone https://github.com/nescode/pollcorn.git
cd pollcorn
pip install -r requirements.txt
./manage.py migrate
./manage.py createsuperuser
```

Browse your localhost with 8000 port. Polls application accessible at

```python
http://127.0.0.1:8000/polls
```
