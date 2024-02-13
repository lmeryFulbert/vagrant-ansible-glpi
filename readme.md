# Stack LAMP Provisionning via Ansible

## Fulbert Team

### @MERY Ludovic

ludovic.mery@ac-orleans-tours.fr

## Prérequis

* VirtualBox	Version 7.0.14 r161095 (Qt5.15.2)

* Vagrant	Version 2.4.1

## Composants installés via Ansible

* OS: Debian 12 64 bits
  
  * Apache 2
  
  * PHP 8.2.7

  * MariaDB

  * Last release glpi

## Usage

    vagrant plugin install vagrant-vbguest
    vagrant up

pour lancer le provisionning

    vagrant provision

## Accès au repertoire de publication

    http://127.0.0.1:8080
