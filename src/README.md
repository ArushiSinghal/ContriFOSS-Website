## Installation

### System Requirements

* Git
* Python 3.6.9
* pip 9.0.1


### Setup
* [Install and configure Git](https://www.linode.com/docs/development/version-control/how-to-install-git-and-clone-a-github-repository/)
* git clone https://github.com/ContriFOSS/ContriFOSS-Website.git
* cd ContriFOSS-Website/src
* sudo apt-get update
* sudo apt-get upgrade
* sudo apt-get install python3 (sudo apt-get upgrade python3)
* python3 -m pip install --upgrade pip (Install Pip)
* sudo apt-get install python3-venv (Virtual Environment)
* python3 -m venv myvenv
* source myvenv/bin/activate (Activate Virtual Environment)
* sudo apt install nodejs
* sudo npm i -g npx
* npm config set proxy http://proxy_host:port (For setting proxy, if required)
* ```npm config delete proxy``` and ```npm config delete https-proxy``` (For removing proxy, if required)
* pip3 install -r requirements.txt

### Start React Server
* Open a New Terminal
* cd frontend
* npm install
* npm run start

### Start Django Server
* Open a New Terminal and activate virtual environment (source myvenv/bin/activate)
* cd FossSite
* python manage.py migrate
* python manage.py makemigrations
* python manage.py runserver
