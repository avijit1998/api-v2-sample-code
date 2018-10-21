# WhatIsMyBrowser.com API 
## Version 2 Sample Code for Python 2.7

### Installation instructions

* Use VirtualEnv to create an environment

    `virtualenv --no-site-packages env`

    This creates an `env/` directory in the `Python27` directory with an empty Python environment.

* Activate the virtual environment

    `source env/bin/activate`

* Install the requirements from `requirements.txt`

    `pip install -r requirements.txt`

    The `requirements.txt` file will install the the "security" version of the excellent "Requests" module.

    http://docs.python-requests.org/

* Copy `config-dist.py` to `config.py` and put your API Key in the variable there.

* Run the various example scripts

    `python user_agent_parse.py`

    `python user_agent_parse_batch.py`

    `python software_version_numbers.py`

    These scripts simply print various outputs to the terminal. Take these examples and integrate them with your system as you require.

* Errors:
    1.`ImportError:No module named` ...
    If you get any error as such you will have to download and install the module using `pip`.
    
    You can check if pip is installed on your system by simply entering `pip` on your terminal/cmd.
    If not recognised then download and intall it first.
    https://bootstrap.pypa.io/get-pip.py
    If you’re on Python 3.2, you’ll need this version https://bootstrap.pypa.io/3.2/get-pip.py


    Suggested module installation (if needed)
    
    `pip install virtualenv`
    `pip install config`
    

