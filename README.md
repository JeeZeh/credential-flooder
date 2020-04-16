# Credential Flooder

I wrote this simple credential flooder to run against servers hosting phishing scams.

___

### Typical Usage

Requires >=Python3.6

Find a server that's hosting some phishing scam and use this to target the POST form that ingests users' data. 

You could use network tools in your browser to check where the data is going. If it's obscured, many phishing sites run on PHP with directory traversal on, some even keep a copy of the PHP in the directory above. Try snoop and see if you can find the source with even more info!

Examine the PHP and find what form headers it's looking for like 'email' and 'password'. Change the credential_flooder.py constants at the top as appropriate.

Clone and modify as appropriate :)
