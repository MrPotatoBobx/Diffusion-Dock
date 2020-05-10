# Diffusion-Dock
a fork of [Team-Diffusion's diffusion dock](https://github.com/Team-Diffusion/Diffusion-Dock)
this fork is made for me to work on it without disrupting the main project
# What is diffusion dock?
Diffusion dock is the dock for the Linux distro, Diffusion Linux.
# Preview 
![](readme_images/example.png)
# Features
* Display icons
* Shows program name when hovering over icon
  
  More features will be added in the future
# Installation
 
 ## Ubuntu and Ubuntu based distros
   Make sure you have pip3 installed, if not install it by running `sudo apt install python3-pip`
   
   First of all we will need to clone the repository, run `git clone https://github.com/MrPotatoBobx/Diffusion-Dock`
   
   After we have cloned the dock we will change our directory in to it via `cd Diffusion-Dock`
   
   To install the dependencies we have to run `sudo apt install python3-pip pkg-config libcairo2-dev libglib2.0-dev libgirepository1.0-dev && pip3 install -r requirements.txt`
   
   Then you can run the dock by running `python3 app.py`
   
   **Please do note this dock is very alpha and is being worked on**
     
   # DISCLAIMER: only works with X11, not Wayland
