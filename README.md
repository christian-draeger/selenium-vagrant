# selenium-vagrant

This is Vagrant file that provides several things to run selenium tests in it or against it (with RemoteWebDriver)

### How to use

  vagrant up
  
### What you get

The vagrant box that will be created mathces the following characteristics:
* OS: Windows Server 2019
* preinstalled stuff needed to run selenium tests
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
