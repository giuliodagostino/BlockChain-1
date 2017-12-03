# BlockChain-1
BlockChain demo built on Python 3.6+ (along with pip) // Use HTTP Client, like Postman or cURL

Installation

Make sure Python 3.6+ is installed.
Install pipenv.
$ pip install pipenv 
Create a virtual environment and specify the Python version to use.
$ pipenv --python=python3.6
Install requirements.
$ pipenv install 
Run the server:
$ pipenv run python blockchain.py
$ pipenv run python blockchain.py -p 5001
$ pipenv run python blockchain.py --port 5002
Docker

Another option for running this blockchain program is to use Docker. Follow the instructions below to create a local Docker container:

Clone this repository
Build the docker container
$ docker build -t blockchain .
Run the container
$ docker run --rm -p 80:5000 blockchain
To add more instances, vary the public port number before the colon:
$ docker run --rm -p 81:5000 blockchain
$ docker run --rm -p 82:5000 blockchain
$ docker run --rm -p 83:5000 blockchain
