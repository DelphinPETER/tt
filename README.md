What is tt
------

**tt** is a simple Bash script for quick access to [**Translation Tools**](https://github.com/DelphinPETER/TranslationTools) from the Terminal.

How to install tt
------

Enter the following lines in Terminal:

    mkdir -p /home/$USER/bin
    curl https://raw.github.com/jackmu95/tt/master/tt > /home/$USER/bin/tt
    chmod 755 /home/$USER/bin/tt
    
How to configure tt
------

Before you can start using **tt** you have to edit some user specific code.<br/>
To edit the code go to `/home/USER/bin/` and open **tt** with your favorite text editor.

The line which has to be edited is:

    # Path to the root directory of the local CyanogenMod source code
    cmDir=/path/to/cm/source/code

After you have edited the user specific line to your conditions save your changes and make sure that the permission of **tt** are still **755 (rwxr-xr-x)**.

If they aren't just enter the following line in Terminal again:

    chmod 755 /home/$USER/bin/tt

How to use tt
------
####After tt is configured you can use it by just typing `tt` in the Terminal.

How to uninstall tt
-----

Enter the following line in Terminal:

    rm /home/$USER/bin/tt