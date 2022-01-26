Installing Anaconda on Ubuntu OS
====================================

In these instructions, you will learn  the process of how to install the latest version (2020.11) of Anaconda on the Ubuntu operating system.


1. As you have Ubuntu running, locate your terminal and open it.
2. Enter this command into the terminal and press the Enter key: 

.. code-block::

			sudo apt install libgl1-mesa-glx libegl1-m esa libxrandr2 libxrandr2 libxss1 libxcursor1 libxcomposite1 libasound2 libxi6 libxtst6
  
3. Next, enter this command into the terminal and press the Enter key:
 
.. code-block::

		  Wget https://repo.anaconda.com/archive/Anaconda3-2020.11-Linux-x86_64.sh -O ~/Downloads/Anaconda3-2020.11-Linux-x86_64.sh

4. Enter this command into the terminal and press the Enter key in order to open the downloads directory:

.. code-block::

      cd ~/Downloads
      
5. As you have the directory open, type this command into the terminal and press Enter key: 
 
.. code-block::

      sudo chmod +x Anaconda3-2020.11-Linux-x86_64.sh
      
6. Type this command into the terminal and press the Enter key: 
 
.. code-block::
  
        ./Anaconda3-2020.11-Linux-x86_64.sh
        
7. View EULA by pressing the down key.
8. Type "yes" in the terminal to continue.  
9. To finalize installation, type this command into the terminal:

.. code-block::

        source ~/.bashrc
        
10. Press the Enter key to finish the installation. In order to test the installation and see if it worked, type this command into the terminal:

.. code-block::

        conda info 
        
11. You now have the latest version of Anaconda installed.         
  
    
