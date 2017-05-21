# TutorSense

## Environment
To run this Web Application on your own server, you'll need to set up a LAMP environment.

I recommend setting up a Virtual Machine for development using a combination of Vagrant and VirtualBox.

Vagrant: https://www.vagrantup.com
VirtualBox: https://www.virtualbox.org

Once these are installed, you can start a vagrant box up using the settings here: https://github.com/TutorSense/xenial-box

And then follow the instructions on setting up Apache2, MySql and PHP here: https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-on-ubuntu-16-04 

After setting this up, you will also want to globally install on the vagrant box:
* Node and NPM: https://tecadmin.net/install-latest-nodejs-npm-on-ubuntu/
* Install curl and git: `sudo apt-get install curl php7.0-cli git`
* Composer: curl -sS https://getcomposer.org/installer | sudo php -- --install-dir=/usr/local/bin --filename=composer

## Installation/Setup
* Run the following commands:
```
$ composer install
$ npm install
```

* Compile dependancies by running
```
$ npm run dev
```
