---
layout: default
title: Install ownCloud
nav_order: 2
---

# Install and configure ownCloud
{: .d-inline-block }
Admin
{: .label .label-green }

## Prerequisites
Before you begin, install [Oracle VirtualBox](https://www.virtualbox.org/wiki/Downloads).

## Install and configure
There are a number of options available to install ownCloud depending on your system and preferences. Refer to the [ownCloud download guide](https://owncloud.org/download/#owncloud-server) for a complete list of options.

The quickest way to install ownCloud is to use a pre-configured virtual appliance. Pre-configured virtual appliances contain operating systems together with ownCloud and the required support applications already installed and configured. Popular examples of these are VirtualBox, ESXi, VMware and KVM. ownCloud provides virtual appliance files for each of these environments.

To install and configure ownCloud using a VirtualBox appliance file, complete the following steps:
1. Using your browser, navigate to the [ownCloud download page](https://owncloud.com/download/).
2. Under `Download ownCloud Server` click on `DOWNLOAD`.
3. Complete the form with your details and select `VirtualBox` from `Download version`.
4. Click `DOWNLOAD OWNCLOUD`.
5. Following a successful download, run VirtualBox on your local system.
6. Click `File`, `Import Appliance` and select your downloaded virtual appliance file.
7. Click `Next` and `Import` to import the virtual appliance.
6. To complete the installation, click `Start` on the virtual appliance and follow the steps in the configuration wizard. For a detailed guide on how to use the configuration wizard, refer to [How to Install the Appliance](https://doc.owncloud.org/server/10.4/admin_manual/appliance/installation/installation.html#configuration-wizard).

Note: Keep a record of the administrator password and server IP address you choose. You need this to configure and manage your ownCloud server.
