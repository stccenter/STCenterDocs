========================================
Installing Anaconda for CentOS users
========================================

Anaconda is a package manager & python distribution. 
It is incredibly useful for data tasks. 
Anaconda provides a bundle of scientific packages that you will use throughout you project task such as NumPy, Sci-kit Learn, Pandas, and more. 
**Installation process is as follows:**

1.	Firstly, inside terminal verify that python is installed, it is recommended to have the latest version. Currently that is Python3
-	Python is probably already installed on your system. On the command line without the brackets type sudo <python --version> 
This Command checks the version of the desired application in our case, python. 

2.	Visit the `Anaconda website <https://www.anaconda.com>`_
 Anaconda website, this is where you will have the choice to install Anaconda versions
-	One the webpage navigate to the menu bar and select products – Induvial Edition, copy the bash (.sh file) installer link

**TERMINAL COMMANDS:**

1.	**Use ``wget`` to download the bash installer**

  Use the follow in commands 

    ``$ mkdir tmp``

    ``$ cd tmp``
  
    ``$ wget https://repo.continuum.io/archive/Anaconda3<release>.sh``
    
2.	**Run bash script to install anaconda3**

Ensure you are in the directory where the installer script downloaded:

    ``$ ls``
    
    ``Anaconda3-5.2.0-Linux-x86_64.sh``
    
    ``bash Anaconda3-5.2.0-Linux-x86_64.sh``
    
    ``source .bashrc`` 
    
3.	**Test installation**

    ``python`` then, ``exit()``
    
   Install a package 
   
    ``conda install numpy``

|
| Developed by: Shyra LaGarde
| Documented by: Shyra LaGarde
| Tested by: -

