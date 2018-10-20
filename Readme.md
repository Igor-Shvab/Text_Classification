
# Text Classifier

## Getting started

This is simple Ensemble Model text classifier that takes input setntences (description of disease or medical problem) and classifies them according to prescribed drug rating.

## Prerequisites

Works on any Unix-based system with python3

## Dependencies

Install [Python 3], [Virtualenv], and third-party dependencies once:

- Mac OS:

  ```bash
  brew install python3
  pip3 install virtualenv
  python3 -m virtualenv --python=python3 env
  source env/bin/activate
  pip3 install -r requirements.txt
  ```

- Debian / Ubuntu

  ```bash
  apt-get install python3 python3-virtualenv
  python3 -m virtualenv --python=python3 env
  source env/bin/activate
  pip3 install -r requirements.txt
  ```

Activate the virtual environment whenever you want to work on this code:

```bash
source env/bin/activate
```

When you have finished, just run:

```bash
deactivate
```

[Python 3]: https://www.python.org/
[Virtualenv]: https://virtualenv.pypa.io/en/stable/
