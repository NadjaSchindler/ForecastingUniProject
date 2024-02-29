Use the requirements.txt file to install all the necessary packages and dependencies to compile the notebook correctly.

There are two options: the pip_requirements.txt is compatible with the pip package manager while the conda_requirements.txt only works for the conda distribution. 


If you want to use pip excecute this command: 

pip install -r pip_requirements.txt


For conda you need this command: 

conda create --name <enter your name> --file conda_requirements.txt