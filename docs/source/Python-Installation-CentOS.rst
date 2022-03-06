========================================
Python installation for CentOS users
========================================

Make sure to update the environment up to date in terms of the package; And make sure to be a root user to do this add “sudo” in front of command line 

Use the following command to ensure all required dependencies are up to date 
``sudo yum update -y``

1. **Install python 3**::

  ``sudo yum install -y python3``

2. **Install pip**::
  
  ``sudo yum install python-pip``

3. **Create a directory for the webservice**::

  ``sudo mkdir aqi-api`` 
  
  ``cd aqi-api``

4. **Create a virtual environment**::

  ``sudo python3 -m venv aqi-api-env`` 
  
  ``source aqi-api-env/bin/activate``
  
5. **Installing a package**
  Use anaconda or pip to install packages, in this guide anaconda is used. To install anaconda use our **Anaconda installation guide**
  Use the following command to test run a package installation, numpy is a widely used package. 
  
  ``conda install numpy`` 
  
  
  
|
| Developed by: Shyra LaGarde
| Documented by: Shyra LaGarde
| Tested by: -
