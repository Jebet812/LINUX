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
This updates 

