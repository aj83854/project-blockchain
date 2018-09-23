### Project files for:
blockchain.py \
A simple python blockchain application for education & research \
Using Flask 1.0.2 & requests 2.19.1
__________________________________
### Code along project using:

**Learn Blockchains by Building One** \
_by Daniel van Flymen, 2017_

https://medium.com/p/117428612f46
___________________________________

## Installation

1. Make sure [Python 3.6+](https://www.python.org/downloads/) is installed.
2. Install [pipenv](https://github.com/kennethreitz/pipenv).

```
$ pip install pipenv
```

3. Create a _virtual environment_ and specify the Python version to use.

```
$ pipenv --python=python3.6
```

4. Install requirements.  

```
$ pipenv install
```

5. Run the server:
    * `$ pipenv run python blockchain.py`
    * `$ pipenv run python blockchain.py -p 5001`
    * `$ pipenv run python blockchain.py --port 5002`

Remember to use an HTML client (httpie, cURL, Postman, etc) to interact with the Flask API.
