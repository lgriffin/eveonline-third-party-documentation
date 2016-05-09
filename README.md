[![Documentation Status](https://readthedocs.org/projects/eveonline-third-party-documentation/badge/?version=latest)](https://eveonline-third-party-documentation.readthedocs.org/en/latest/)

# eveonline-third-party-documentation
Documentation for EVE Online third-party developers. This covers things like the XML API, CREST, the Static Data Export (SDE), and SSO. You can read the latest version of the documentation [here](http://eveonline-third-party-documentation.readthedocs.org/en/latest/).
Read the instructions below if you'd like to contribute.

# Developing
## Setup
You will need to have python, pip and virtualenv installed (install virtualenv using pip) then run the following commands from inside the repo directory:

### Windows
    virtualenv venv
    venv\Scripts\activate
    pip install -r requirements.txt

### Linux/mac
    virtualenv venv
    source venv/bin/activate
    pip install -r requirements.txt

## Running
    cd docs
    make livehtml

# Contributing
Please organize your submissions by API "section" and submit a separate pull
request for each change.  We suggest you create a separate branch for each
pull request.  This will make it easier to work on multiple changes
simultaneously.

For example, to contribute a change to the XML API docs for character  MarketOrders:

1. Create a branch (say, "marketorders") on your fork of [ccpgames/eveonline-third-party-documentation](https://github.com/ccpgames/eveonline-third-party-documentation)
2. In your branch, make your changes to `docs/xmlapi/character/char_marketorders.md`.  Be sure to follow the standards for each section of the documentation.
3. Submit a pull request from yourfork:marketorders to ccpgames:master

Please also add your name to the CONTRIBUTORS file (sorted by first name please!).
