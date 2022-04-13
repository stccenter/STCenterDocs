Installing Gephi on Ubuntu OS
=============================

In these instructions, you will learn the process of how to install the latest version of Gephi (0.9.2) on the Ubuntu operating system.

1.) As you have Ubuntu running, locate your terminal and open it.

2.) In order to use Gephi, you will have to use Java installed on your virtual machine. If you do not have Java  installed, type these commands into the terminal:

	``sudo add-apt-repository ppa:openjdk-r/ppa``
	
	``sudo apt update``
	
	``sudo apt install openjdk-8-jdk openjdk-8-jre``
	
3.) Next, in order to download the latest version of Gephi, enter this command into the terminal and press the Enter key:

	``wget -q --show-progress https://github.com/gephi/gephi/releases/download/v0.9.2/gephi-0.9.2-linux.tar.gz``
	
4.) To extract Gephi, type this command into the terminal and press enter:

	``tar xzf gephi-0.9.2-linux.tar.gz``
	
5.) To start Gephi, type this command into the terminal and press enter:

	``./gephi-0.9.2/bin/gephi``
	
6.) Now, you should see Gephi 0.9.2 load up, and is ready to use!



Developed by: Leslie Dawn

Documented by: Shyra LaGarde

Tested by: -
