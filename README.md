pyslate
=========


This is a text translation library implemented in Python. It uses the Google Translate API for language detection and translation.


Version
----

1.0

Tech
-----------

`pyslate` uses the following libraries and APIs to work properly:

* re - The python regular expression library
* codecs - This module defines base classes for standard Python codecs (encoders and decoders) 
* urllib and urllib2 - For requests and encoding operations
* sys - This module is required for some system functions
* google translate API - This API is used for text translation

Usage
--------------

Following are the main usage patterns of pyslate.

```python

>>> from pyslate import Translator
>>> tr = Translator()
>>> tr.translate('hello world', from_lang='en', to_lang='de')
u'hallo Welt'
>>> tr.detect("hallo Welt")
u'de'
```
