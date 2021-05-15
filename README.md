# Aws-Lambda-Python
Return random word from Lambda API and DynamoDB

HOW TO USE:

Windows
Install npm from: https://nodejs.org/en/
Today - Download for Windows (x64)
14.17.0 LTS - Recommended For Most Users

Install wscat application (https://github.com/websockets/wscat)
From a administrator instance of Power Shell run:
sudo npm install -g wscat

Connect to Lambda API
wscat -c wss://3w0zg1oeh0.execute-api.us-east-2.amazonaws.com/production

Run a JSON formated query:
{"action":"word"}

Linux

sudo apt-get update
or maybe sudo apt-get upgrade?

sudo apt install npm
sudo npm install -g wscat
wscat -c wss://3w0zg1oeh0.execute-api.us-east-2.amazonaws.com/production
{"action":"word"}
