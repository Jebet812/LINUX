#       LINUX
##  ADDING AND REMOVING SOFTWARE
There key methods for adding new software.

### Using ``apt`` to Hand Software
In Debian-Linux the default software manager is Advanced Packaging Tool, or ``apt``, whose primary command ``apt-get``. You can use the command to download and install new software package but you can also update and upgrade software with it.

#### Searching for a Package
To check whether the package you need is available from your repository (a place where your operating system stores information), use ``apt`` tools search function. ``apt-cache search`` *keyword*

#### Adding Software
``apt-get`` is used to download software from the operating system's default repository in the terminla followed by keyword ``install``. For example ``apt-get install snort``

#### Removing Software
Use ``apt-get remove snort`` *command* to remove snort or any software you want to remove.</br>
The command does not remove configuration files, hence you can reinstall in future without reconfiguring.</br>
Use ``apt-get purge snort`` *command* to remove configuration files at the same time as the package or any package you want to remove. 

#### Updating Package
This updates the list of package available for download from the repository. ``apt-get update`` will search through package in system and check whether updates are available.

#### Upgrading Packages
Upgrading will upgrade the package to latest version in the repository. Type the command ``apt-get upgrade``

### * Adding Repositories to Your source.list files*
*Repositories* serves to hold software for a particular distribution in Linux. Each distribution has its own repositories of software developed and configured for that distribution - that may not work well or at all, with other distributions hnce it is worth adding a back up repository or two that your repository can searc through incase it doesn't find a specific software in the current one.</br>
The repositories the system will searc for are in the *source.list* file which is located in at */etc/apt/sources.list.*<br/>
Ubuntu divide repositories into separate categories
- *Main:* Contains supported opensource software
- *Universe:* Contains community-maintained opensource software
- *Restricted:* Contains proprietary device drivers
- *Multiverse:* Contains software restricted by copyright or other legal issues
- *Backports:* Contains packages from later releases


