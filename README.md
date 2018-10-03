# TodoVagrant - (c) Andre Lohmann (and others) 2018

## Maintainer Contact

 * Andre Lohmann
   <lohmann.andre (at) gmail (dot) com>

## purpose

This Vagrant development machine creates a lokal development environmen for the cloud-training Todo Application (https://github.com/andrelohmann/cloud-training_todo-app).

## usage

  * git clone this repositoroy
  * if necessary create a "custom_vars.yml" file and set your custom local
  * run vagrant up

The vagrant machine will clone the ragarding TodoApplication into the application/ subfolder. It also installs the runtime environment as well as a lokal test mailserver (mailhog).

After a successfull vagrant up run, the application provides the following endpoints:
  * http://todo.lokal - The Todo Application
  * http://todo.lokal/phpmyadmin - phpmyadmin - User: root, Password: vagrant
  * http://mail.todo.lokal - The lokal Mailserver
