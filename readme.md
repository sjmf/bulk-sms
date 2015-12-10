# Simple Twilio bulk SMS client (in Python)

## Description
This script will send mass SMS out to many people using the Twilio API.

Your contacts must be specified in a CSV file, where the first column is the phone number.

The message is read from a message file and sent to all contacts.

Contacts will not recieve the message twice as the script will remove duplicate numbers automatically.

Finally, a cost estimate is provided and the user is prompted to confirm (Y/n) before sending commences.

## Defaults and Variables
Message file: `message.txt`
CSV numbers file: `participants.csv`

You will also need to fill in your Twilio account SID, auth_token, and 'from' number.

Use responsably :)

## Licence

Public domain, 2015
