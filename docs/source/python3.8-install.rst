Steps to Install Python 3.8.10 in Windows 11
=========================================

1. Go to `<https://www.python.org/>`_.
2. Scroll down to view the different versions of Python. Once you see the version “Python 3.8.10”, click on it to view the information/files regarding this version.
3. Towards the bottom of the page, there will be a list of downloadable files. Depending on your Operating System, you should either choose “Windows installer (32-bit)” or “Windows installer (64-bit)”. My computer is a 64-bit OS so I chose Windows installer (64-bit).
4. Once you click the file, the download will begin.
5. When the download is complete, open the file. There will be an installation window to help you begin the installation process.
6. Before pressing "Install Now", click the box “Add Python 3.8 to PATH” at the bottom of the window. Adding Python to PATH makes it possible to run Python from your command prompt.
7. Click the “Install Now” button.
8. To confirm installation, open Command prompt and type “python --version”. If the installation was successful, it should display the version information and the Python command prompt. 

Steps to creating Virtual Environment
----------------------------------

The pupose of a virtual environment is to create an independent environment for Python projects. This means that each project can have its own dependencies separate from others of a different Python project.

1. Open Command Prompt.


2. Type: python -m venv byron env

“byron env” is an example name of an environment. You have the option to name it anything.

3. To activate the environment, type:

C:\\Users\\byron\\Documents>byron env\\Scripts\\activate.bat

4. To install packages using pip, type: pip install package-name

Example: (byron env) C:\\Users\\byron\\Documents>pip install numpy

