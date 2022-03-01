## **Python installation and virtual environment set up**

Make sure to update the environment up to date in terms of the package; And make sure to be a root user to do this add “sudo” in front of command line 

Use the following command to insure all required dependencies are up to date 
`sudo yum update -y`

**Step 1: Install python 3**
`sudo yum install -y python3`

**Step 2: Install pip**
`sudo yum install epel-release`
`sudo yum install python-pip`

**Step 3: Create a directory for the webservice**
`sudo mkdir aqi-api`
`cd aqi-api`

**Step 4: Create a virtual environment**
`sudo python3 -m venv aqi-api-env`
`source aqi-api-env/bin/activate`

