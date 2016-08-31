# xen Orchestra installer script

The single line installation required the following steps from a root shell. 

Confirm your VM's IP Address before starting the script so you know where to login to. 

##Usage:
The default username and password are applied, admin@admin.net and admin for the password

    sudo bash
    <password>
    sudo curl https://raw.githubusercontent.com/iFloris/xenorchestra_installer/master/xo_install.sh | bash
    <password>
    
    
If you don't want NFS capabilities run "sudo apt-get remove nfs-common".

##Build
This script builds a working self-compiled [Xen Orchestra](https://github.com/vatesfr) install on a fresh VM install of [Ubuntu Server 16.04.1 LTS (GNU/Linux 4.4.0-31-generic x86_64)](http://www.ubuntu.com/download/server/thank-you?version=16.04.1&architecture=amd64).

##Reason for forking
This script was tested on august 30th 2016 because of a post on Reddit [here](https://www.reddit.com/r/homelab/comments/5031i9/xenserver_vs_esxi/). In recent months, I have seen quite a few mentions of the automated XOA builder script no longer working, but I was able to build it fine about 8 months ago. So I decided to test it again, using any possible enhancements. In this fork, a recent enhancement was incorporated, which I believe helps building the script on current systems.

##Credits
Uses the awesome script [here](https://github.com/scottalanmiller/xenorchestra_installer) by [scottalanmiller](https://github.com/scottalanmiller) only changed by incorporating the enhancement proposed by [Danp2](https://github.com/Danp2) in his pull request [here](https://github.com/Danp2/xenorchestra_installer/commit/33f08faec83a094ab53756bc773b85e98eb3e51f).
