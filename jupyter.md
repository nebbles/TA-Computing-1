# Setting up Jupyter on Macintosh

Open up a terminal.

## Homebrew

First, install [Homebrew](https://brew.sh) if you haven't already installed it. If you already have Homebrew, you can skip this step.

To check if you have Homebrew installed, run this:

> brew -v

You should see a response like this:

    Homebrew 2.1.1
    Homebrew/homebrew-core (git revision 11402; last commit 2019-05-04)
    Homebrew/homebrew-cask (git revision 821a8; last commit 2019-05-03)

If instead it is not recognised, run this command to install it:

> /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

## Installing Python

All Macs come bundled with a system version of Python. This is traditionally Python 2.7 and should generally be left alone.

To install the latest version of Python (3+) run the following command:

> brew install python3

## Installing Jupyter

With Python now installed, first upgrade the Python package manager (called *pip*):

> python3 -m pip install --upgrade pip

Then, install Jupyter with pip:

> python3 -m pip install jupyter

## Running Jupyter

To run Jupyter, enter the following command into a terminal:

> jupyter notebook

## Shutting down Jupyter

When Jupyter is running, there is two ways to close it down.

1. On the web interface for Jupyter notebook, choose shutdown from the menu.
2. On the terminal window which is currently running Jupyter (where you typed in `jupyter notebook`), press **Ctrl+C** to exit.
