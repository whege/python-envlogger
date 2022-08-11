# python-envlogger
Python logger with output directed based on working environment

## Motivation
This project stemmed from some code I wrote for work. While I needed logs to print to the terminal during development, I wanted to be able to configure logs to go to a file/database when deployed to production.

However, I didn't want to rewrite or reconfigure my Logger or logging statements when pushing to deployment. 

To that end, I created this module as an extenion of the built-in logging package in Python, with the main difference being that the Logger class reads the environment from a config file and directs the output appropriately.
