### Install Jypyter on Ubuntu 14.04
-----------
This guide is going to show how to install Jupyter with non-root user

#### Chaper 01: Setup Jupyter

1. Update your system

```
$ sudo apt-get update
```

2. Install Python 2.7, Python Pip and Python Deverlopment:

```
$ sudo apt-get -y install python2.7 python-pip python-dev
```

3. Install Jupyter Notebook:

```
$ sudo apt-get -y install ipython ipython-notebook
$ sudo -H pip install jupyter

```

After installing, running Jypyter by command:
```
$ jupyter notebook
```
*Note*: If you are running on Ubuntu-Desktop then after this command, Jypyter will open a new tab on your web client (Chrome, FireFox, etc). However in case you are running on Ubuntu-server then you have to set up a tunnel from your laptop to your sever to use Jypyter on server.

#### Chaper 02: Setup a tunnel on Windown

Please refer to this link: https://www.digitalocean.com/community/tutorials/how-to-set-up-a-jupyter-notebook-to-run-ipython-on-ubuntu-16-04