# xenorchestra_installer

The single line installation required the following steps from a root shell. 

Confirm your VM's IP Address before starting the script so you know where to login to. 

The default username and password are applied, admin@admin.net and admin for the password

    sudo bash
    <password>
    sudo curl https://raw.githubusercontent.com/iFloris/xenorchestra_installer/master/xo_install.sh | bash
    <password>
    
    
If you don't want NFS capabilities run "sudo apt-get remove nfs-common".

##Credits
Uses the awesome script [here](https://github.com/scottalanmiller/xenorchestra_installer) by [scottalanmiller](https://github.com/scottalanmiller) only changed by incorporating the enhancement proposed by [Danp2](https://github.com/Danp2) in his pull request [here](https://github.com/Danp2/xenorchestra_installer/commit/33f08faec83a094ab53756bc773b85e98eb3e51f)


