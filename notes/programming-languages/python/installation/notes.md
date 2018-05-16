# Installing Python and Pip

Before you can execute Python programs on your machine, you need to install the Python command-line utility. In the recent past, there has been a movement from Python version 2 (2.x) to Python version 3 (3.x) and there is still some lingering awkwardness as a result. Previous semesters have accommodated both versions of Python, but this semester we are going to be exclusively using Python 3.x, specifically 3.6.x.

When you install Python, you also get Pip. Pip is a command-line utility for installing third-party Python packages. We will primarily be using a different tool for this purpose, but more on package management later.

## Detecting Installations

First thing's first. Let's see if Python is already installed on your machine:

```sh
# Mac Terminal:
which python # check for Python in general, or Homebrew-installed Python Version 2.x
which python3 # check for Homebrew-installed Python Version 3.x

# Windows Command Prompt:
where python
````

If you see a filepath output, it means Python is installed at the location specified, so you can advance to the version detection instructions below.

If you see an empty result or an error message, that usually means Python is not installed, so you can skip to the OS-specific installation instructions further down below.

## Detecting Versions

Let's see which version of Python is installed:

```shell
python --version #> Python 3.6.5
pip --version #> pip 9.0.1 from /usr/local/lib/python3.6/site-packages (python 3.6)
```

If Python 3.6.x is installed, great! No need to install it again.

If Python 3.6.x is not installed, follow the OS-specific instructions below to install it.

If Python 2.x is installed and you're not sure how to install version 3.x without causing conflicts (especially on Windows), ask the professor for guidance.

## Installation

To install Python, see one of the following guides, based on your operating system:

  + [Installing Python on Mac OS](on-mac-via-homebrew.md)
  + [Installing Python on Windows OS](on-windows.md)

After Python is installed, you should be able to run Python commands from the command line. Depending on your installation, you will either be running `python` and `pip` (website-downloaded Python on Windows or Mac), or `python3` and `pip3` (Homebrew-installed Python on Mac).