## Unsintall Python from ubuntu
  1. ls /usr/bin/python*
  2. sudo apt-get remove python3.5
  3. sudo apt-get remove --auto-remove python3.5
  4. sudo apt-get purge python3.5
  5. sudo apt-get purge --auto-remove python3.5

## Install python on ubuntu
  1. sudo apt install software-properties-common -y
  2. sudo add-apt-repository ppa:deadsnakes/ppa
  3. sudo apt install python3.10 -y
  4. python3.10 --version

## For virtual env
  1. sudo apt install python3.10-venv -y
  2. python3.10 -m venv venv

## Install git
  1. sudo apt install git
  2. git --version

## Install pip
  1. sudo apt install python3-pip -y
  2. pip3 --version
