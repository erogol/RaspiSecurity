# RaspiSecurity
Home Surveillance with Raspberry with only ~100 lines of Python Code.
For technical details check the realted [medium post](https://hackernoon.com/raspberrypi-home-surveillance-with-only-150-lines-of-python-code-2701bd0373c9). Hope you like it.

# Installation to a new Raspberry2 B+

## Install necessary libraries 
- ```sudo apt-get update```
- ```sudo apt-get install build-essential python2.7-dev python-setuptools```
- ```sudo apt-get install python-opencv```
- ```sudo easy_install pip```
- ```sudo pip install picamera```

## Setup config files
- Set email address to be used by the agent. 
- Set your email address to be noticed for each alert

## Run the agent
- ```python pi_surveillance.py -c <config_file> ```




