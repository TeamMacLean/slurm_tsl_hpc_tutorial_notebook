---
title: "SLURM Job and Resource Manager"
author: "Ram Krishna Shrestha"
date: "29 January 2020"
output: html_document
---



## A Guide to HPC SLURM job and resource manager in TSL HPC

This notebook is intended to get you starting with submiting your scripts/programs and monitoring them in HPC using command-line. 

### What is SLURM?

Before we start, you must have this question. In short, SlURM is an open source, highly scalable cluster management and job scheduling system for large and small High Performance Computing (HPC) Linux clusters. Here in NBI, we use SLURM for job management in the HPC cluster.

### Pre-requisites

To get you starting with TSL HPC, first you need TSL HPC account. If you don't have TSL HPC account, please contact Dr. Ram Krishna Shrestha, Bioinformatician in Room G27, who will then request NBI computing department to setup an account for you. You will be then notified once your account is up. To access TSL HPC using your account, you will need an application in your local machine (laptop or desktop PC) that can connect the HPC server. Linux and MacOS users can use an application called "Terminal" while windows machine users can use "PuTTY". If you have any problem installing PuTTY, please contact our IT specialist Chris Rickett. The second method of login in to TSL HPC is using online "Open On Demand" from your internet browser. We will now see these method below.

### How to login in to TSL HPC

#### Method 1

Open a terminal app in Linux/MacOSX or PuTTY in Windows. A screen opens up showing your machine username and ID. My terminal screen like this when I open it.
![New terminal just opened](/home/shrestha/SLURM_HPC_Training_Material/figures/blank_terminal.png "New terminal")

To login, we use "ssh" command followed by your TSL username and then "@hpc.tsl.ac.uk". Type the password (same password you use for TSL email) when it asks you. My username is shrestha. See below how I login.

![SSH to TSL HPC](/home/shrestha/SLURM_HPC_Training_Material/figures/ssh_login.png "TSL HPC login")

After you type the correct password, you will see the welcome text, showing that the login has been successful and you are in the home folder of your account in the HPC.

![Welcome to TSL HPC](/home/shrestha/SLURM_HPC_Training_Material/figures/after_login.png "You are logged in")

#### Method 2

NBI computing has provided web based method accessing HPC and job/files management. Once your TSL HPC account is ready to use, go to https://ood.hpc.nbi.ac.uk. Enter your TSL username and password. You will see the following screen on successful login.

![Open On Demand Login Screen](/home/shrestha/SLURM_HPC_Training_Material/figures/ood_login.png "Using HPC with Open On Demand Service")

Check the menu options - files, jobs, clusters and interactive apps. See below for brief explanation of the options:

1) Files: This is for navigation of files in your HPC HOME area. User can do some basic file operations like renaming, copying, deleting and downlaoding the files.
2) Jobs : Users can view the list of active jobs currently running on HPC or compose a new job for submission.
3) Clusters: This gives terminal app like access to the HPC from the web. Enter the password for your HPC account and then the screen looks same as in the terminal app.
4) Interactive Apps: This one is for running Jupyter notebook in HPC using HPC resources. Running Jupyter notebook is not covered here.


That's it. Now, you are logged in and ready to start.





