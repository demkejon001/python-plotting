# Python Plotting

Simple Python plotting examples using matplotlib.

## Installation Requirements

These examples require the installation of matplotlib. You can easily
install this using:

```
sudo dnf install python-pip
sudo pip install pandas matplotlib
```

I prefer to use a virtual environment, so that every Python program
can have its own dependencies. In this case, use the following to
create and activate a virtual environment with the required
packages. Do this in the top level directory of this code.

```
sudo dnf install python-pip
sudo pip install virtualenv
virtualenv env
source env/bin/activate
pip install -r requirements.txt
```

## Installation Errors

1. lapack/blas not installed

Error:

```
numpy.distutils.system_info.NotFoundError: no lapack/blas resources found
```

Fix:

```
sudo dnf install lapack-devel
```

## Usage

You can run the script using:

```
python plot.py
```

This will create various plots for you.
