Steps to Install Python 3.9.7 in Windows 11
=========================================

1. Go to `<https://www.python.org/>`_.
2. Scroll down to view the different versions of Python. Once you see the version “Python 3.9.7”, click on it to view the information/files regarding this version.
3. Towards the bottom of the page, there will be a list of downloadable files. Depending on your Operating System, you should either choose “Windows installer (32-bit)” or “Windows installer (64-bit)”. My computer is a 64-bit OS so I chose Windows installer (64-bit).
4. Once you click the file, the download will begin.
5. When the download is complete, open the file. There will be an installation window to help you begin the installation process.
6. Before pressing "Install Now", click the box “Add Python 3.9 to PATH” at the bottom of the window. Adding Python to PATH makes it possible to run Python from Command Prompt.
7. Click the “Install Now” button.
8. To confirm installation, open Command Prompt and type “python --version”. If the installation was successful, it should display the version information and the Python command prompt. 

.. image:: ../images/python-screenshot.png
    :width: 480px
    :align: center
    :height: 175px
    :alt: Verify python installation

Steps to Creating Virtual Environment
----------------------------------

The pupose of a virtual environment is to create an independent environment for Python projects. This means that each project can have its own dependencies separate from others of a different Python project.

1. Open Command Prompt.

2. You will need to create a directory/folder for your virtual environment. To do this: type "mkdir" followed by a space, type a name for your created folder, and press enter. 

3. To place your virtual enviroment inside your created folder, you will need to display the directory for that folder. To do this: type "cd" followed by a space, enter the name of your folder, and press enter.

.. image:: ../images/v-env.step3.png
    :width: 400px
    :align: center
    :height: 200px
    :alt: Placing virtual environment inside a folder
    

4. To create your environment, type "python -m venv demo-env". As a note, "demo-env" is an example name for the environment. You have the option to name it anything.

5. To activate the environment, type "demo-env\\Scripts\\activate.bat".

.. image:: ../images/v-env.step5.png
    :width: 500px
    :align: center
    :height: 75px
    :alt: Activating virtual environment 
   

6. To install packages using pip, type: "pip install package-name". In the image below, the package name is "numpy".

.. image:: ../images/v-env.step6.png
    :width: 550px
    :align: center
    :height: 40px
    :alt: Installing packages using pip


|
| Developed by: Byron Pritchett, Jr.
| Documented by: Byron Pritchett, Jr.
| Tested by: -
