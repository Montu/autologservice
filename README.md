autologservice
==============

Registery scripts to make windows system automatically logon and start and stop a service(bstack4win server)

# autologon.reg

This script changes the windows registry to enable autologin for an user. By default "DefaultUserName" is set to
akshay and "DefaultPassword" to password. So change these values with respect to your computer and run the
script. To run either double click on the file and click on a warning message or goto cmd and type:
regedit /S autologon.reg. This will silently run the script and alter registry settings.

