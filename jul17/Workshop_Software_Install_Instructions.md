# Demystifying AI Workshop Optional Software Download and Install Mentoring Session
 
Date & Time: 
Friday July 21st, 2017 6-9 pm
 
Location: 
NextSpace Coworking Berkeley
2081 Center St, Berkeley, CA 94704
 
It is recommended that attendees install Python, Anaconda, Jupyter Notebook, Scikit Learn, and TensorFlow on their laptops prior to attending.
 
## Mentoring Slack Channel
We created a slack channel for easy communication and mentoring during the event. 

-Join [Accel.AI Slack](https://slackpass.io/accelai)

-Join #demystify-ai-workshop
 

## Quick Install Method

We have prepared Docker images (Python 2.7 & 3.6) with instructions as a quick install method.

https://github.com/AccelAI/datascience-docker/blob/master/README.md


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

 3) Customzie & paste the following into the terminal and press **[Enter]** to start the environment installation:
 
    `
    conda create --prefix ~/anaconda3/envs/[name of your environment] python=[version of python you want installed] scipy     scikit-learn nose readline pandas seaborn jupyter tk graphviz requests pyyaml ipywidgets tensorflow pytorch theano
    `
     
    **For example:**  _conda create --prefix  ~/anaconda3/envs/**myTFenv** python=**3.6.1** scipy scikit-learn nose readline
                      pandas seaborn jupyter tk graphviz requests pyyaml ipywidgets tensorflow pytorch theano_

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
   conda create --prefix ~\anaconda3\envs\[name of your environment] python=[version of python you want installed] scipy scikit-learn nose readline pandas seaborn jupyter tk graphviz requests pyyaml ipywidgets tensorflow pytorch theano
   `

**For example:**  _conda create --prefix  ~\anaconda3\envs\ **myTFenv** python= **3.6.1** scipy scikit-learn nose readline pandas seaborn jupyter tk graphviz requests pyyaml ipywidgets tensorflow pytorch theano_


 4) Once the above has run successfully, there will be a message about activating the environment

5) activate [name of your environment]

   **For example:**  _activate **myTFenv**_

6)  your command-line prompt should change to reflect that you are in and active environment.
    
    **For example:**  _$(myTFenv) C:\Users\ [your username]_

7)  Once the environment is active and you are at the command prompt again, type:
    
    **_pip install keras_**


## Additional Presentation Specific Links or Setup

### Why AI Works: The Epistemeology of Deep Learning

-[Presentation Slides](https://drive.google.com/a/accel.ai/file/d/0B5S9_hdLh22jTUJNR0RFVWtqMHFVamI0Sllrbk9CN1NZbUZJ/view?usp=sharing) 

### Intro to Machine Learning with George McIntire

-Fork & Clone Github repo: https://github.com/GeorgeMcIntire/intro_ml_presentation

### Word Embeddings Workshop with Rachel Thomas, PhD 

-Fork & Clone Github repo: https://github.com/fastai/word-embeddings-workshop

### Generating Text with Recurrent Neural Networks using Keras with Melissa Roemmele

-Fork & Clone Github repo: https://github.com/roemmele/keras-rnn-demo

### Building Chatbots with Michael Khait 

-Install the latest version of NodeJS (https://nodejs.org/en/download/)

-Create Facebook Developer Account (https://developers.facebook.com)

-Create Sample Facebook Page (https://www.facebook.com/pages/create/)

-Create Microsoft Account (https://dev.botframework.com/)

-[Presentation Slides](https://drive.google.com/a/accel.ai/file/d/0B5S9_hdLh22jQU5jWjl1OVlOWXdsLXg3NTQxYldZWnpMSmhN/view?usp=sharing)

### Can a machine control the human body? with Lukasz Kidzinski, PhD

-Fork & Clone Github repo: https://github.com/stanfordnmbl/osim-rl#getting-started

-[Presentation Slides](https://drive.google.com/a/accel.ai/file/d/0B5S9_hdLh22jd0tlN3A1d3RxZ0hlTHd4eXRYQl9RQVZBTjBN/view?usp=sharing)

### Molecular Machine Learning with Bharath Ramsundar

-[Presentation Slides](https://drive.google.com/a/accel.ai/file/d/0B5S9_hdLh22jLW41Wm1yWVJwM3FCQmRTMTF1WWgyYmZ0VWsw/view?usp=sharing)

## Smart Villages Workshop

-Doc: https://drive.google.com/drive/folders/0B5jWGSpbXP6SYTVRemhzQWFKSDg

## Product Market Fit in AI with Masha Kubyshina

-[Presentation Slides](https://docs.google.com/presentation/d/19qHFZKy9VgHGlZUE_E1nEJM-g9dMsfAumJr4XJbfJdw/edit?usp=sharing)

### Personalization Redefined Through Machine Learning with Sudha Subramanian

-[Presentation Slides](https://drive.google.com/a/accel.ai/file/d/0B5S9_hdLh22jbjV3cTJraEdpRWZpeTNCQXVPT3lZSzlUN2Qw/view?usp=sharing)

## Machine Learning Tools with Pankaj Kumar

-[Presentation Slides](https://drive.google.com/a/accel.ai/file/d/0B5S9_hdLh22jUUtjYUxKQVZ5MlRaejR3SHRnRnZqamlRTFhF/view?usp=sharing)
