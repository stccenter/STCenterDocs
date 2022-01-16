Installing Python 3.9 on Ubuntu OS
====================================

In these instructions, you will learn the process of how to install Python 3.9 on the Ubuntu OS by adding the Deadsnakes PPA (Personal Package Archives) to your system repository list. 

1. As you have Ubuntu running, locate your terminal and open it.

2. To install the package, type this command into the prompt:

		sudo apt-get install software-properties-common
    
3. Type “y” into the prompt and press the enter key to continue.

4. To add the Deadsnakes PPA to your system’s repository, type this command into the prompt:

			sudo add-apt-repository ppa:deadsnakes/ppa

5. Press “Enter” in order to continue with the process.

6. Make sure to update your system’s repository list. In order to do this, type this command into the prompt: 

			sudo apt-get update
      
7. Press the enter key. 

8. To initialize the installation of Python, type this command into the prompt:

			sudo apt-get install python3.9
      
9. Press the enter key.

10. Type “y” into the prompt and press the enter key to continue.

11. Allow the installation to complete. To check the installation is done, type this into the command prompt:

      python3.9 --version

12. Installation is complete!

.. code-block::
   :caption: A cool example

       The output of this line starts with four spaces.

.. code-block::

       The output of this line has no spaces at the beginning.
