# Demystifying AI Workshop Optional Software Download and Install Mentoring Session
 
Date & Time: 
Friday July 21st, 2017 6-9 pm
 
Location: 
NextSpace Coworking Berkeley
2081 Center St, Berkeley, CA 94704
 
It is recommended that attendees install Python, Anaconda, Jupyter Notebook, Scikit Learn, and TensorFlow on their laptops prior to attending.
 
## Mentoring Slack Channel
We created a slack channel for easy communication and mentoring during the event. 
Join Accel.AI Slack
Join #demystify-ai-workshop
 

## Quick Install Method

We have prepared 2 Docker images (Python 2.7 & 3.6) as a quick install method.


## Step by step instructions for software download and installation on Mac & Windows

Package Documentation:

Python - https://www.python.org/downloads/

Anaconda - https://docs.continuum.io/anaconda/install/

Jupyter Notebook - http://jupyter.readthedocs.io/en/latest/install.html

Scikit Learn - http://scikit-learn.org/stable/install.html

Tensorflow - https://www.tensorflow.org/versions/r0.11/get_started/os_setup.html





### Instructions for Mac:

 1) Download (https://www.continuum.io/downloads) & install Anaconda.  
     (We strongly recommend using python 3.6.1 version)

 2) Open a terminal and  `cd` to your home directory (`cd ~/)

 3) Paste the following into the terminal and press [Enter] to start the environment installation:
conda create --prefix ~/anaconda3/envs/<name of your environment> python=<version of python you want installed> scipy scikit-learn nose readline pandas seaborn jupyter tk graphviz requests pyyaml ipywidgets tensorflow pytorch theano
     
For example:  conda create --prefix  ~/anaconda3/envs/myTFenv python=3.6.1 scipy scikit-learn nose readline pandas seaborn jupyter tk graphviz requests pyyaml ipywidgets tensorflow pytorch theano

 4) Once the above has run successfully, there will be a message about activating the environment

 5) source activate <_name of your environment_>
      For example:   source activate myTFenv

6)  your command-line prompt should change to reflect that you are in and active environment.
    For example: (myTFenv)  My-MacBook-Pro: ~ myusername$
 
7)  Once the environment is active and you are at the command prompt again, type:
     pip install keras

You should now be up and running and able to code, run examples, or launch a Jupyter Notebook.


_____________________________________________


### Instructions for Windows:

 1) Download (https://www.continuum.io/downloads) & install Anaconda.  
     We strongly recommend using python 3.6 version
     TtensorFlow for python 2.7.13 is not supported on Windows)

 2) Open a command prompt (NOT PowerShell!) and `cd` to your home directory
     ( cd  C:\Users\<your user name>)

 3) Paste the following into the terminal and press [Enter] to start the environment installation:

conda create --prefix ~\anaconda3\envs\<name of your environment> python=<version of python you want installed> scipy scikit-learn nose readline pandas seaborn jupyter tk graphviz requests pyyaml ipywidgets tensorflow pytorch theano

For example:  conda create --prefix  ~\anaconda3\envs\myTFenv python=3.6.1 scipy scikit-learn nose readline pandas seaborn jupyter tk graphviz requests pyyaml ipywidgets tensorflow pytorch theano`


 4) Once the above has run successfully, there will be a message about activating the environment

5) activate <_name of your environment_>`
     For example:  activate myTFenv

6)  your command-line prompt should change to reflect that you are in and active environment.
    For example: $(myTFenv) C:\Users\<your username>  >

7)  Once the environment is active and you are at the command prompt again, type:
     pip install keras


## Additional Presentation Specific Links or Setup


Word Embeddings Workshop with Rachel Thomas, PhD 
Fork & Clone Github repo: word-embeddings-workshop

Building Chatbots with Michael Khait 
Install the latest version of NodeJS (https://nodejs.org/en/download/)
Create Facebook Developer Account (https://developers.facebook.com)
Create Sample Facebook Page (https://www.facebook.com/pages/create/)
Create Microsoft Account (https://dev.botframework.com/)

