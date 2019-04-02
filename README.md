**Project**: microblog

**Description**: A poor man's clone of twitter. This project follows the [Flask Mega Tutorial] by Miguel Grinberg.

## Getting Started

git clone the repo

### Prerequisites

You should have Python installed. Specifically version `2.7.*`


## Running the app
cd into the microblog folder
```shell
cd microblog/
```

Install [virtualenv](https://virtualenv.pypa.io/en/latest/) if you don't already have it.

```shell
pip install virtualenv
```

create a virtual environment and activate it

```shell
virtualenv venv
source venv/bin/activate
```

Run the command to install all requirements
```shell
pip install -r requirements.tx
```

Run the application by starting the local server
```shell
export FLASK_APP=microblog.py
flask run
```

## Built With

*   [Flask Web Framework](http://flask.pocoo.org/)
