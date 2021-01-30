# Kernel Arguments

In Pyabr software you can power on it on **GUI** mode or **CLI** mode,

### We can run Pyabr as:

- **Default Kernel Argument**
- **GUI Argument**
- **CLI Argument**
- **CLI Login Argument**
- **CLI New Process Argument**
- **CLI Exec Argument**
- **CLI Switch User Argument**
- **GUI Splash Argument**
- **GUI Login Argument**
- **GUI Desktop Argument**

### Default Kernel Argument

In this case you want to run Pyabr without any arguments:

```shell
python vmabr.pyc
```

> In Linux use python3 instead of python

## GUI Argument

With this argument you can run your Pyabr in **Graphical User Interface** mode:

```shell
python vmabr.pyc gui
```

## GUI Splash Argument

After Runing in **GUI** mode Pyabr should pass this steps:

[![Backend window](https://raw.githubusercontent.com/manijamali2003/pyabr-docs/main/images/00009.png "Backend window")](https://raw.githubusercontent.com/manijamali2003/pyabr-docs/main/images/00009.png "Backend window")
1. Backend window
   
[![Splash window](https://raw.githubusercontent.com/manijamali2003/pyabr-docs/main/images/00010.png "Splash window")](https://raw.githubusercontent.com/manijamali2003/pyabr-docs/main/images/00010.png "Splash window")
2. Splash window
   
[![Login window](https://raw.githubusercontent.com/manijamali2003/pyabr-docs/main/images/00011.png "Login window")](https://raw.githubusercontent.com/manijamali2003/pyabr-docs/main/images/00011.png "Login window")
3. Login window
   
[![Enter window](https://raw.githubusercontent.com/manijamali2003/pyabr-docs/main/images/00012.png "Enter window")](https://raw.githubusercontent.com/manijamali2003/pyabr-docs/main/images/00012.png "Enter window")
4. Enter window

[![Desktop window](https://raw.githubusercontent.com/manijamali2003/pyabr-docs/main/images/00013.png "Desktop window")](https://raw.githubusercontent.com/manijamali2003/pyabr-docs/main/images/00013.png "Desktop window")
5. Desktop window

You can enter Pyabr as **Splash**, **Login**, etc:

```shell
python vmabr.pyc gui-splash
```

## GUI Login Argument

```shell
python vmabr.pyc gui-login
```

## GUI Enter Argument

```shell
python vmabr.pyc gui-enter [username]
```

> Use your username after gui-enter argument

## GUI Desktop Argument

```shell
python vmabr.pyc gui-desktop [username] [password]
```

> Use your username and password after gui-desktop

## CLI Login

CLI Login the same as GUI login but in **Command Line Interface** mode.

```shell
python vmabr.pyc login
```

## CLI User

CLI Enter can enter to your user in **CLI** mode.

```shell
python vmabr.pyc user [username] [password]
```

## Create an Exec Process

You can run Pyabr commands outside of Pyabr:

```shell
python vmabr.pyc exec [command] [arguments] ...
```

- For example:

```shell
python3 vmabr.pyc exec echo Hello World
```