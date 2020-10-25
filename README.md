# phpvuln

[![Python 3.x](https://img.shields.io/badge/python-3.x-yellow.svg)](https://www.python.org/)

phpvuln is an open source OWASP penetration testing tool written in Python 3, that can speed up the the process of finding common PHP vulnerabilities in PHP code, i.e. command injection, local/remote file inclusion and SQL injection. It uses different searching and matching techniques to find the results.

## Screenshot

![Screenshot](images/screenshot1.png)

## Installation

You can download phpvuln by cloning the Git repository:

``` bash
git clone https://github.com/ecriminal/phpvuln.git
```

Install the required PIP packages:

``` bash
python -m  pip install -r requirements.txt
```

## Usage

To get the list of all options use:
 `python phpvuln.py -h`
