#PyUniSend
PyUniSend is a simple API wrapper for interacting with [unisender.com](http://www.unisender.com/ru/?a=112233)
##Requirements
Python 2.7 or later.  
A UniSend.com account and API key. You can see your API keys [here](https://www.unisender.com/ru/user_info/?a=112233).
##Installation
    pip install pyunisend
##Usage
    from pyunisend import PyUniSend
    api = PyUniSend('YOUR APIKEY')
    api.getLists()

## Notes
API parameters must be passed by name. For example:  

    api.createList(title='NewList')

##Copyrights

* Copyright (c) 2011 Klimin Mikhail. Please see LICENSE.txt for details.