## Setup instructions

This Python course requires a computer that is set up with the appropriate software and tools. This document provides the steps in order to prepare your own computer. 

## What tools will we be using?

The core tools are:

* Python 3.6+ (for new installations we will use 3.8) 
* Anaconda Distribution
* Jupyter Notebooks + Jupyter Lab

We will also use a large collection of third-party Python packages and library. A full list can be found in the [`environment.yml`](https://github.com/TiesdeKok/acctg-579b/blob/master/environment.yml) file. 

## Some important remarks:

> But I already have Python installed on my computer, I surely don't need to do all this?

I'd like everyone to complete the steps, even if you already have Python set up on your computer. Doing so will make sure that everyone has the same setup, this makes solving technical issues a lot more managable. You can have multiple Python installations / Conda environments on your computer, so you don't need to uninstall your current setup. 

One exception is if you already have the Python 3.7 or 3.8 version of Anaconda installed on your computer, in that case you can skip step 1. 

> Do I have to use Jupyter Notebooks? I'd much rather use tool .... 

There are many ways to write Python code and ultimately I recommend you to use whatever you want. However, I would appreciate it if you could use Jupyter Lab + Jupyter Notebooks during this Python course. This makes it easier for everyone to work together and also makes it easier to solve technical problems as they arise. The material is not specific to Jupyter so after the course you switch back to whatever tool you prefer without any problem. 

> I keep getting errors?! What do I do... 

Some of you might encounter problems when following the steps below, but don't worry, I am here to help! I've created a text channel called `setup-help` in the Discord channel. Please post a message in that channel if you need help and I will respond ASAP to help you get it resolved. 

> Everything that you show is on Windows, but I am on Mac OS / Linux? 

All of my demonstrations will be on Windows, however, I'll try to include pointers in cases where I know there are differences between Windows and Unix (i.e. Mac OS and Linux). You should be able to following along with any operating system without too much trouble. 

> How long should it take me to complete these steps?

On a decent computer it shouldn't take more than 30 to 45 minutes to get everything set up. Install Anaconda and the Conda environment will take some time, but besides that should be relatively quick. However, this is obviously conditional on you not running into any problems. 

**I strongly recommend to try and complete these steps as soon as possible, this gives us time to resolve any problems before the course starts.**  

## Setup steps:

###  **Step 0:** watch primer on using the command line / terminal: 

> How to change directory using the command line or terminal:  
> 
> [Panopto: How to change directory using the command line or terminal](https://uw.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=9d8e0760-391c-4ef3-9310-ac2a01269af0)

###  **Step 1a:** install the Anaconda Distribution with Python 3.8.

**NOTE:** Anaconda just switched to Python 3.8, so just install 3.8 (in the video it mentions 3.7).


> How to install the Python Anaconda Distribution:  
> 
> [Panopto: How to install the Python Anaconda Distribution](https://uw.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=0febfea1-3d60-4345-93d0-ac2a0129cc28)

###  **Step 1b:** learn how to interact with the Anaconda Distribution.

> How to interact with Python Anaconda Distribution:  
> 
> [Panopto: How to interact with Python Anaconda Distribution](https://uw.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=4fe48220-4381-4aca-ba55-ac2a012b29ac)

###  **Step 2:** (temporarily) download the acctg-579b Github repository

The `ACCTG-579B` GitHub repository includes the `environment.yml` file that you need for step 3. So make sure to create a local copy of this repository: [repository](https://github.com/TiesdeKok/acctg-579B)  

> How to create a local copy of a Github repository:  
> 
> [Panopto: How to create a local copy of a Github repository](https://uw.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=650dd080-751e-44f2-9b6b-ac2a0128101d)

###  **Step 3:** create the `researchPython` conda environment

> **Note:** the `environment.yml` in the video is slightly different as the one will install. Just follow the steps in the video but anytime there is a mention of `limpergPython` replace it with `researchPython`. The steps are exactly the same (just the name and `environment.yml` are different). 
> 
> How to create and use a Python Conda environment:  
> 
> [Panopto: How to create and use a Python Conda environment](https://uw.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=a0f0c45e-e667-4ba5-99cb-ac2a01269b29)

### **Step 4:** test environment by starting a Jupyter Lab session

> **NOTE:** anytime there is a mention of `limpergPython` replace it with `researchPython`.
> 
> How to start a Jupyter Notebook or Jupyter Lab server:  
> 
> [Panopto: How to start a Jupyter Notebook or Jupyter Lab server](https://uw.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=b226f64a-3d90-449f-a410-ac2a01269b69)

### **Step 5:** run the test notebook to make sure everything is 100% set up correctly. 

> **Steps:**
>
> 1. Make sure you have Jupyter Lab open (follow Step 4)  
> 2. In Jupyter Lab, find and open the notebook called `setup_test.ipynb` (should be in the folder you downloaded in step 2)  
> 3. Run all the cells in this notebook and check for any errors.  
> 4. Follow the steps provided in the notebook if you experience problems (or contact me if you get stuck).  