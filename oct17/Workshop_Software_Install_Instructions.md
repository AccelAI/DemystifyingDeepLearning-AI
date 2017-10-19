# Software Download and Install Mentoring Session
 
Date & Time: 
Tuesday October 17th, 2017 6:30-9 pm
 
Location: 
Google Launchpad 
301 Howard St, 4th Floor
San Francisco, CA 94105


Thanks to our sponsors, Google Launchpad for hosting the space and food for this event!

 
Instructions for installation of Python, Anaconda, Jupyter Notebook, Scikit Learn, TensorFlow, and PyTorch.
 
## Mentoring Slack Channel
We created a slack channel for easy communication and mentoring during the event. 

-Join [Accel.AI Slack](https://slackpass.io/accelai)

-Join #demystify-ai-workshop
 



## Step by step instructions for software download and installation on Mac & Windows

Package Documentation:

[*Python*](https://www.python.org/downloads/)

[*Anaconda*](https://docs.continuum.io/anaconda/install/)

[*Jupyter Notebook*](http://jupyter.readthedocs.io/en/latest/install.html)

[*Scikit Learn*](http://scikit-learn.org/stable/install.html)

[*Tensorflow*](https://www.tensorflow.org/versions/r0.11/get_started/os_setup.html)





### Instructions for Mac:

 1) [**Download**](https://www.continuum.io/downloads) & install Anaconda.  
     (We strongly recommend using python 3.6.1 version)

 2) Open a terminal and  `cd` to your home directory ( `cd ~/` )

 3) Customize & paste the following into the terminal and press **[Enter]** to start the environment installation:
 
    `
    conda create --prefix ~/anaconda3/envs/[name of your environment] python=[version of python you want installed] scipy     scikit-learn nose readline pandas seaborn jupyter tk graphviz requests pyyaml ipywidgets tensorflow theano
    `
     
    **For example:**  _conda create --prefix  ~/anaconda3/envs/**myTFenv** python=**3.6.1** scipy scikit-learn nose readline
                      pandas seaborn jupyter tk graphviz requests pyyaml ipywidgets tensorflow theano_

 4) Once the above has run successfully, there will be a message about activating the environment

 5) source activate [name of your environment]
 
    **For example:** _source activate myTFenv_

6)  your command-line prompt should change to reflect that you are in and active environment.

    **For example:** _(myTFenv)  My-MacBook-Pro: ~ myusername$_
 
7)  Once the environment is active and you are at the command prompt again, type:

    `pip install keras`

You should now be up and running and able to code, run examples, or launch a Jupyter Notebook.


_____________________________________________


### Instructions for Windows:

 1) [**Download**](https://www.continuum.io/downloads) & install Anaconda. 
     We strongly recommend using python 3.6 - **TensorFlow for python 2.7.x on is not available for Windows**

 2) Open a command prompt (_**NOT PowerShell!**_) and `cd` to your home directory:
    
    `cd  C:\Users\[your user name]`

 3) Customize & Paste the following into the terminal and press **[Enter]** to start the environment installation:

   `
   conda create --prefix ~\anaconda3\envs\[name of your environment] python=[version of python you want installed] scipy scikit-learn nose readline pandas seaborn jupyter tk graphviz requests pyyaml ipywidgets tensorflow theano
   `

**For example:**  _conda create --prefix  ~\anaconda3\envs\ **myTFenv** python= **3.6.1** scipy scikit-learn nose readline pandas seaborn jupyter tk graphviz requests pyyaml ipywidgets tensorflow theano_


 4) Once the above has run successfully, there will be a message about activating the environment

5) activate [name of your environment]

   **For example:**  _activate **myTFenv**_

6)  your command-line prompt should change to reflect that you are in and active environment.
    
    **For example:**  _$(myTFenv) C:\Users\ [your username]_

7)  Once the environment is active and you are at the command prompt again, type:
    
    **_pip install keras_**



## Quick Install Method

Only use this method if you are already comfortable with Docker.

We have prepared Docker images (Python 2.7 & 3.6) with instructions as a quick install method.

https://github.com/AccelAI/datascience-docker/blob/master/README.md


## Additional Presentation Specific Links or Setup

These will be added as speakers turn in their links.

### Intro to Machine Learning with George McIntire

-Fork & Clone Github repo: https://github.com/GeorgeMcIntire/intro_ml_presentation

### Data Cleaning with Kristin Henry

-Fork & Clone Github repo: https://github.com/KristinHenry/workshopOct2017

Slides: https://docs.google.com/presentation/d/1oOV7lVE5ZCniZVHHdFm0tRCzY4E7Ls_XLL88G5RS0jg/edit?usp=sharing

### Molecular Machine Learning with Bharath Ramsundar

Slides: https://docs.google.com/presentation/d/1BHrBk2QbARHCl-nOjCioNEgeyx82OHG5QyLBHYFhjlI/edit?usp=sharing

### Hands on Intro to Pytorch with Abhishek Sharma

-Fork & Clone Github repo: https://github.com/abhi21/pytorch-tutorial

### AI for Banking & Insurance with Ian Foley

Slides: https://drive.google.com/a/accel.ai/file/d/0B5S9_hdLh22jeHQxSF9idHItWmVqSWh2ZjR4SWxyaDE2YkNn/view?usp=sharing

### Representation Learning with Nathaniel Tucker

Slides: https://docs.google.com/presentation/d/11cgq2sDBzkjTo0-bLiJFThSN1IStqEcbLrduKcIKLRc/edit?usp=sharing

### Future of Transportation with Sarah Feldman

Slides: https://drive.google.com/file/d/0BxXyZpLZVAKbbEpuY3RnWFF3clE/view?usp=sharing

