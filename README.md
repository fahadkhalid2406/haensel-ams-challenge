# haensel-ams Recruitment Challenge

## About this porject
This project is a Python implementation of the Google Gmail API, designed to showcase the use of the API for basic email sending and searching functionality. The code is divided into two main parts: one for sending emails and one for searching for messages in the Gmail mailbox.

To use the code, you need to set up a test Gmail account and enable the Gmail API. Once you have obtained the necessary credentials, you can use the send_email function to send emails and the search_messages function to search for messages that contain specific keywords in the subject or body.

Overall, this project is a simple but effective demonstration of how to use the Google Gmail API in Python to send and search for emails, and can serve as a starting point for more complex Gmail API integrations.

## Technical Aspects
This project uses the following stack:
- Python
- Google API

## Setup Guide
- ### Enable the Gmail API and Create Credentials

# How To Use?
python main.py

# What it does?
The scripts is intended to scrub booking_tracking_detail  data

# Configuration File
The configuration file contains the configurations to delete the data from the target table.

The configuration file `yaml` should look like this:

```yaml
db_url: <database endpoint>
db_username: <database username>
db_password: <database password>
db_port: <database port>
schema: <schema_name>
start_date: <start date for deletion>
end_date: <end date for deletion>
batch_size: <no of days>
```