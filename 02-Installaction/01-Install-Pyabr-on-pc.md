#### Install Pyabr on PC/Laptop

Our plan for installation of Pyabr:

- Git source, use pip for install
- Running setup installer step by step
- Find installed directory

##### Git source

You can get latest version of Pyabr at github by running this command:
```shell script
git clone https://github.com/manijamali2003/pyabr.git
```

If you want to install the stable version of Pyabr you can install it with PyPI:
```shell script
pip install pyabr
python -m pyabr
```

##### Running the setup installer

In installing with PyPI the setup install is automatically run but in git source you should run the setup installer by this commands:
```shell script
cd pyabr
python setup.py
```

##### Install step by step

[![Installing step by step](https://raw.githubusercontent.com/manijamali2003/pyabr-docs/main/images/00002.png "Installing step by step")](https://raw.githubusercontent.com/manijamali2003/pyabr-docs/main/images/00002.png "Installing step by step")

Now it's a setup install that you can install Pyabr without any compile source or run extra commands, etc
Please click `Next` button.

[![Installing step by step](https://raw.githubusercontent.com/manijamali2003/pyabr-docs/main/images/00003.png "Installing step by step")](https://raw.githubusercontent.com/manijamali2003/pyabr-docs/main/images/00003.png "Installing step by step")

You can choose your installaction directory for Pyabr or skip this page, for choosing please click `Browse` button.

[![Installing step by step](https://raw.githubusercontent.com/manijamali2003/pyabr-docs/main/images/00004.png "Installing step by step")](https://raw.githubusercontent.com/manijamali2003/pyabr-docs/main/images/00004.png "Installing step by step")

You can make an empty directory for Pyabr, please create or choose an empty directory.

[![Installing step by step](https://raw.githubusercontent.com/manijamali2003/pyabr-docs/main/images/00005.png "Installing step by step")](https://raw.githubusercontent.com/manijamali2003/pyabr-docs/main/images/00005.png "Installing step by step")

In this case you should type your informations:
- **In Hostname** choose a name for you cloud software.
- **In New Root password** please choose a strong password.
- **In Pick a username** enter your username for the administor user in Pyabr 
- **In New Password** choose a strong password for your administor user

[![Installing step by step](https://raw.githubusercontent.com/manijamali2003/pyabr-docs/main/images/00006.png "Installing step by step")](https://raw.githubusercontent.com/manijamali2003/pyabr-docs/main/images/00006.png "Installing step by step")

In this page you should choose your local language for your cloud software and choose your cloud software interface.

We have two interfaces in Pyabr:

- Command Line Interface (CLI)
- Graphical User Interface (GUI)

If you want to lock the **guest** user please skip this page by leave the guest user checkbox.
Else you can click the **guest user** for unlock the guest user.

Guest user in Pyabr is very small user without configuration controller database and it doesn't have any password, It means that you can go to command line or desktop without password in guest user login.

[![Installing step by step](https://raw.githubusercontent.com/manijamali2003/pyabr-docs/main/images/00007.png "Installing step by step")](https://raw.githubusercontent.com/manijamali2003/pyabr-docs/main/images/00007.png "Installing step by step")

Please complete you information after that click the `Finish` button and wait about 1 second for installing Pyabr

##### Finding the installed directoy

[![Installing step by step](https://raw.githubusercontent.com/manijamali2003/pyabr-docs/main/images/00008.png "Installing step by step")](https://raw.githubusercontent.com/manijamali2003/pyabr-docs/main/images/00008.png "Installing step by step")

After installaction of Pyabr you can find your installed directory for running Pyabr.

For running the Pyabr click right, Open in Terminal, or in Windows File > PowerShell run:

```shell script
python vmabr.pyc
```

That is!