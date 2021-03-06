# Installation

**fgmk** is packed as a regular Python project, in the [Python Package Indexer](https://pypi.python.org/pypi/fgmk).

As such, installation is fairly easy, and easier if you already have Python
installed.


## Recommended Install and run

If you are already familiar with Python, just use the commands below in your
terminal to install and run **fgmk**.

    pip3 install fgmk
    fgmk


### Windows Installation

![Installation on Windows with pip](win_fgmk_install.gif)

In Windows, install Python 3 from [www.python.org](https://www.python.org/downloads/),
and then open **cmd.exe** and type (press enter after):

    python -m pip install fgmk

To run, you can type the following in **cmd.exe** or the **run...** prompt:

    python -m fgmk

If your python/scripts folder is in your Windows PATH, you can omit the
preceding `python -m` command, and just type `pip install fgmk` and then `fgmk`.

#### Upgrading

The easier way to upgrade your version of `fgmk` when a new one is released, is
to type:

    pip install --upgrade fgmk

If for some reason it doesn't work, you can also try

    pip uninstall fgmk
    pip install --no-cache-dir fgmk

### Unix install and run

First you need `pip3` for `Python3`.

- in Ubuntu or Debian, open the terminal and use `sudo apt install python3-pip`.

   - After you will be able to run `pip3 install fgmk`. You can just type `fgmk` at command line to launch the editor.

   - In Ubuntu, **fgmk** will be also added to the Unity Applications entry.

#### Upgrading

The easier way to upgrade your version of `fgmk` when a new one is released, is
to type:

    pip3 install --upgrade fgmk

If for some reason it doesn't work, you can also try

    pip3 uninstall fgmk
    pip3 install --no-cache-dir fgmk


## From Source Installation

Clone this repository, meet the dependencies and install this with pip3.

    git clone https://github.com/ericoporto/fgmk.git
    cd fgmk
    pip3 install .


## Running from source

Clone this repository, meet the dependencies and type `python3 -m fgmk`

    git clone https://github.com/ericoporto/fgmk.git
    cd fgmk
    python3 -m fgmk


## Dependencies

This tool is written using Python 3. Needs `pillow`, `numpy` and `PyQt5` -
you can `apt install python3-pyqt5` and similar (in Ubuntu) or use pip.

If you satisfy all dependencies you don't need to install, and can run from
source.

***Experimental compatibility to python2*** (2.7 and on) is added to versions above
0.3.0 . Note that Python 2.7 pip doesn't provide an easy way to install PyQt5 so
you will have to install it on your own - if you are in Ubuntu, use `sudo apt install python-pyqt5`
