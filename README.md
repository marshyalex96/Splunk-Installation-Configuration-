Splunk installation & Configuration with Linux.

Objective: Here I am going to present how to build splunk using linux (in the mere future I will also build one for windows using vmware) show casing how to Install it in both GUI and CLI method (Although  using GUI is a user friendly for everyone especially for begginers, however learning to use the command line interace is a very powerful tool and is often provided better efficency, flexibilty and create scripts to automate task, making it ideal for system admins and IT specailist). Current version on my OS is Linux Mint 22.3 cinnamon 64-bits.
Primary Purpose: Splunk enterprise on Linux is a pretty sturdy data platform developed to aggregate, search, index and analyze logs  with  an abundance of machine generated data in real time. Linux provides a cost effective operating environment, stabilize operational intelligence.  

** Skills Learned **


Understanding the installation process of splunk in various environments.
optimize performance on learning to configure splunk settings and data ingestions
Learn to manage, modify, and define knowledge object for data analysis 
engage in simulations to gain practical knowledge and ensure readiness for a real-world applications.

** Tools Used **

Oracle Virtual Box ( using windows on Virtual machine)
Terminal command for splunk installion

1- Go to the Splunk Site
2- Create an account, if so login
3- Download the MSI installer ( in this scenario we'll be downloading splunk enterprise 10.2.1 on windows using the oracle virtual box)
<img width="1500" height="571" alt="1 - 4QDeT4A" src="https://cdn.phototourl.com/uploads/2026-03-22-ee02cc20-a32a-418c-af9f-0fa1acd7df40.png" />
4-we will need to know what  will be done with our data once the configuration is complete, this is why its imperative to know what we are reading to comprehend all your enterprise information
5-we going to customize options, so first we must check the agreement box and proceed to  "Customize Options" even if we don’t change the default configurations.
6-Next we are given an option to select where we going to install splunk at 
7- Install Splunk as a local System
8- Set the credentials
9- after setting up the credentials it will launch and  ask to please wait
10- After its installation, go and try to connect to: https://127.0.0.1:8000 where it will ask for your credentials you're asked to create.

