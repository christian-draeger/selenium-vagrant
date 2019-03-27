# selenium-vagrant

This project provides a Vagrant file with several pre-configured things to be able to run selenium tests either directly in the box or via remote webdriver. 

Box has been tested with: Mac OSX Mojave / VirtualBox 5.2.20 / Vagrant 2.2.4

### How to use

	vagrant up
  
### What you get

The vagrant box fulfills the following characteristics:
* OS: Windows Server 2019
* preinstalled stuff
  * JDK8
  * several browsers
    * IE11
    * Chrome
    * Firefox
    * Opera
  * Selenium Standalone (to enable Remote control)
  * several Selenium Drivers
    * IE11
    * Chrome
    * Firefox
    * Opera
  * Git
  * Gradle
  * Maven
  * Chocolatey
