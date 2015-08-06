# sdk-python    [![Build Status](https://magnum.travis-ci.com/egodolja/sdk-python.svg?token=9z5hnp59uHpbBpKa445s&branch=master)](https://magnum.travis-ci.com/egodolja/sdk-python)
Python SDK for the Authorize.Net API

Installations
--------------------------------------
- python 2.7
- Editor of your choice (I used PyDev for Eclipse)
- pyxb 1.2.4
 *install python before pyxb 

Run the following to get pyxb and nosetests:
- pip install pyxb
- pip install nosetests
 
Generating classes from xsd
--------------------------------------
- use the pyxbgen script from PyXB
- run the following:
 python [path to pyxbgen] -u [link to xsd schema] -m [name of module to contain the classes]
- refer to generateObjectsFromXSD.bat in the scripts folder to see how it's used

Testing
--------------------------------------
- Tests available are: unit tests, mock tests, sample code
- use nosetests to run all unittests 



