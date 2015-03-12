# Deployer-VDev

A simpler way to get things up and Running on Your development machine. 
It's just a vagrant box with a lot of tools bundled.

So far I put the following batteries:
* An Ubuntu Trusty Vagrant base box;
* Nginx environment with PHP-FPM point to **/sites** folder;
* Phpmyadmin;
* RVM with ruby **2.2.0**;
* Python 2.7 with virtualenv and PIP;
* Php Composer;
* Node and NPM;
* Wp-cli;
* And much more I can't remember now!

This repo has a skelecton needed to init the tool and a brief WIKI and Issue tracker.
Hope You Enjoy it! If You have any questions leave Your requests and I will sure check them out.

# How to start working?

There is two simple ways:

* Using this repo: Just clone this repo then start vagrant. It will do the magic for You.


    git clone https://github.com/joepreludian/deployer-udev.git
    cd deployer-udev
    vagrant up


* If are You wanting a more clean, vagrant way, you can do the following:


    cd <folder_you_want_deployer_in>
    vagrant init joepreludian/deployer-udev
    vagrant up 


# Thank You!
=)
