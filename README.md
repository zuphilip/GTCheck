GTCheck
--------
![Python 3.7](https://img.shields.io/badge/python-3.7-yellow.svg)
![license](https://img.shields.io/badge/license-Apache%20License%202.0-blue.svg)

## Overview
**Check changes in your OCR Ground Truth**

If the Ground Truth data is version controlled by an git repository, than you can use 
"GTCheck" to validate and commit your modification. 
Therefore GTCheck will display the original linetext and the modified version as well as the
corresponding image.

## Installation

This installation is tested with Ubuntu and we expect that it should
work for other similar environments similarly.

### 1. Requirements
- Python> 3.6

### 2. Copy this repository
```
git clone https://github.com/JKamlah/GTCheck.git
cd GTCheck
```

### 3. Installation into a Python Virtual Environment:

    $ virtualenv venv/
    $ source venv/bin/activate
    $ pip install -r requirements.txt
    $ python setup.py install

## Process steps

### Start the process

    $ gtcheck path/to/repo

### Setup Page
In the first page you can set up your git credentials and select the branch or create a new branch for commiting the modfications.

### GTCheck Pagee
In this page you can see and edit the modifications and the original text. 

The modifications can be committed (with the commitmessage), skipped (if not clear what to do), added to the stage mode and later can be committed all at once or can be stashed (keep the original version).

Copyright and License
--------

Copyright (c) 2020 Universitätsbibliothek Mannheim

Author:
 * [Jan Kamlah](https://github.com/jkamlah)

**GTCheck** is Free Software. You may use it under the terms of the Apache 2.0 License.
See [LICENSE](./LICENSE) for details.
