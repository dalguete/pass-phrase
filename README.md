# pass-phrase (DEPRECATED)
Utility script used to pass a passphrase to a ssh key that needs one, but with no
user prompt.

Useful when you have ssh-keys protected with a passphrase and need to set them
using and automatic process, with no prompt or user interaction.

Appeared as a necessity when dealing with some Docker configurations, that required
access to key protected sites, but current keys were also passphrase protected.

Ubuntu PPA
==========

You can find the package as a PPA here https://launchpad.net/~dalguete/+archive/ubuntu/pass-phrase

Sidenote: About My Experience Creating Deb Packages Plus Ubuntu's PPA
---------------------------------------------------------------------

http://dalguete.github.io/#about-my-experiences-creating-deb-packages-plus-ubuntus-ppa
