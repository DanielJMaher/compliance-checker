# Installing Compliance-Checker on Ubuntu


## Installing SWIG on Ubuntu

```
sudo apt-get install swig
```

## Installing Udunitspy

In your Python virtual environment that you set up for Compliance-Checker

```
pip install udunitspy
```

## Testing your UDUnitspy installation

In your Python virtual environment that you set up for Compliance-Checker

Run Python with the `python` command

```
Python 2.7.3 (default, Apr 10 2013, 06:20:15) 
[GCC 4.6.3] on linux2
Type "help", "copyright", "credits" or "license" for more information.
>>> from udunitspy import Unit
>>> 
```

If you don't see an error then udunitspy was succesfully installed, and you can now finish the installation of the compliance checker.

## Installing lxml on Ubuntu

### Get the libxml2 and libxslt packages

```
sudo apt-get install libxml2-dev
sudo apt-get install libxslt1-dev
pip install lxml
```

## Installing Compliance Checker

```
pip install compliance-checker
```

## Testing your compliance checker installation:

Run python on your virtual environment and try:

```
from compliance_checker.runner import ComplianceCheckerCheckSuite
```

If it succeeds, then the Compliance Checker should be working correctly.


