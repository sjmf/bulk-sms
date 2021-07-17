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


## Assistance and contributions

Issues guide:

1. When asking for help, please include the *complete* error message, including the line number, and information about the troubleshooting procedures you've already tried.
2. Ensure you remove any personally-identifying information from issues. This includes phone numbers and individuals' names.
3. This code is provided as-is. Feature requests are great, but it is expected that you provide the code.

Unfortunately, issues which do not follow this guide will be closed. Thank you.

Pull requests are awesome and really help. If you have code to contribute, raise a pull request.

## Licence

Public domain, 2015

Please use responsibly :)
