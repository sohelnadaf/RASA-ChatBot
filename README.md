# RASA-ChatBot  
# for Windows(OS)

## step 1 : Install the Python development environment

Make sure the Microsoft VC++ Compiler is installed, so python can compile any dependencies. You can get the compiler from Visual Studio. Download the installer and select VC++ Build tools in the list.
Install Python 3 (64-bit version) for Windows.

### C:\> pip3 install -U pip

## step 2 :  Create a virtual environment (strongly recommended)

Tools like virtualenv and virtualenvwrapper provide isolated Python environments, which are cleaner than installing packages systemwide (as they prevent dependency conflicts). They also let you install packages without root privileges.

Create a new virtual environment by choosing a Python interpreter and making a .\venv directory to hold it:

### C:\> python3 -m venv ./venv

Activate the virtual environment:

### C:\> .\venv\Scripts\activate

## step 3 : Install Rasa Open Source

First make sure your pip version is up to date:

### $ pip install -U pip
To install Rasa Open Source:

### $ pip install rasa
