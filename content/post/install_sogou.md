+++
title = "How to install Sogou input on Ubuntu 16.04"
date = "2017-09-26T15:16:50+10:00"

math = false
highlight = true
tags = ["software","ubuntu"]
summary = "a step-by-step guide"

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++

## Download
download software package from [here](http://pinyin.sogou.com/linux/).

## Preparation
If the default language of your Ubuntu system is English, first install the required language support and make fcitx as your input method system.

![ figure 1](/img/install_sogou/1.png  "install language support") 

if you like being more google-style, give google pinyin a try:
        sudo apt-get install fcitx-googlepinyin

## Install
1. install the .deb with with the package manager, or using the following command.

        sudo apt-get install ./sogoupinyin_2.1.0.0082_amd64.deb 

2. Restart your computer to be able to see  Sogou input in the text entry list

3. Remove all the shortcut for toggling input except for the one that scrolls from all selections. See images attached. This is to avoid possible conflicts between different hot key settings.

![ figure 2](/img/install_sogou/2.png  "Hot key settings") 
![ figure 3](/img/install_sogou/3.png  "Hot key settings") 
