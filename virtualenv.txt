------------------VIRTUAL ENVIRONMENT--------------------------
SETTING UP AND USING VIRTUAL ENVIRONMENT IN UBUNTU
----------------------
WHY TO USE VIRTUALENVIRONMENT
It allows you to run different version of the same library or framework , so that upgrading won't render your software useless

SETTING UP
1 install virtual environment with the command
	"pip3 install virtualenv"
2 to create a virtual environment first create a directory in, say Desktop, by name vname
3 cd into vname and run the following command to create a virtual environment
	"python3 -m venv name"
4 to activate the virtual environment use (you have to be in the directory vname or you have to specify the path)
	"source name/bin/activate"
5 it will be activated	

USING 
now you can use your virtual environment to download different libraries/framework to use without interfering with your system software

NOTE : the software, you install in venv, cannot be use by os
