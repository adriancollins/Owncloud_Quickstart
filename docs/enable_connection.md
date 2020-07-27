---
layout: default
title: Enable user connection to ownCloud using port 8080
nav_order: 4
---

# Enable user connection to ownCloud using port 8080
{: .d-inline-block }
Admin
{: .label .label-green }

Note: You must have your server root password to change the ownCloud default port.

To change the port number used to connect to ownCloud, complete the following steps:
1. Open the ownCloud text console.
2. Enter this command to edit the file `sudo nano /etc/apache2/ports.conf`. Note: you will be asked for the administrator password here.
3. Replace `Listen 80` with `Listen 8080`.
4. Press the keys `^X` to exit the file. Type `Y` to save your changes.
5. Enter this command to edit the file `/etc/apache2/sites-enabled/000-default.conf`.
6. Replace `<VirtualHost *: 80>` with `<VirtualHost *: 8080>`.
7. Press the keys `^X` to exit the file. Type `Y` to save your changes.
8. To restart the web service, enter `sudo service apache2 restart`.
9. Test the change using your browser by navigating to `your_ownCloud_IP:8080`.

If the changes does not work, you may need to restart your server.
