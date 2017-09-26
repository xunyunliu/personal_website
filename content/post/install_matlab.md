+++
title = "How to install Matlab 2017b on Ubuntu 16.04"
date = "2017-09-26T14:51:08+10:00"

math = false
highlight = true
tags = ["software","ubuntu"]
summary = "a step-by-step guide"
# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++

## Download software
Go to the [download page](https://au.mathworks.com/downloads/) and download the installation file as a zip.

You may have to log in using your matlab credentials before downloading the installation file.

## Install
1. unzip the installation file to anywhere you like.
2. open terminal, type the command below:
		
		sudo sh install

3.  change any settings as you see fit and install the software to its preferred location `/usr/local/MATLAB`
4. active MATLAB with your credentials

## Create desktop entry (optional)
Type the following commands in the terminal.

```sh
sudo wget http://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png -O /usr/share/icons/matlab.png
sudo touch /usr/share/applications/matlab.desktop
sudo gedit /usr/share/applications/matlab.desktop
```
Paste the following into the document and save it.

```
#!/usr/bin/env xdg-open
[Desktop Entry]
Type=Application
Icon=/usr/share/icons/matlab.png
Name=MATLAB R2017b
Comment=Start MATLAB - The Language of Technical Computing
Exec=matlab -desktop -useStartupFolderPref
Categories=Development;
```

Press `super` and then you should be able to find the MATLAB icon in the Unity Search.

## Change initial working directory (optional)

By default, Matlab startups with the folder in which you run the matlab command. To use the folder specified by the Initial working folder preference, use the `-useStartupFolderPref` startup option and change the initial working directory as below.


On the `Home` tab, in the Environment section, click `Preferences` Select `MATLAB` > `General`. Choose an option for the `Initial working folder` preference.

Enjoy using Matlab!



