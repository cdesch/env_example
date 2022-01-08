# dotenv test

## Setup

Create new `venv`

    python3 -m venv venv

Activate `venv`

    source venv/bin/activate

Install requirements

    pip install -r requirements.txt

## Run

Run Script in Root Project directory with `.env` in the same directory.

    python myscript.py

Expected output

    (venv) ➜  env_example$ python myscript.py 
    1234

Run script inside module (sub directory) with `.env` in parent

    (venv) ➜  env_example$ python mymodule/another_script.py 
    1234
