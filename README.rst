SOMANET-OS
==========

Download the last stable version of SOMANET OS
----------------------------------------------

To obtain the last stable version of SOMANET OS, just clone it in a recursive way:

:code:`git clone --recursive https://github.com/synapticon/SOMANET-OS.git`


Upgrading your SOMANET OS version
---------------------------------

If you already cloned the SOMANET OS package and want to upgrade to obtain the last changes, go on your terminal to the directory and execute:

:code:`git pull`

:code:`git submodule update`


Accessing the SOMANET OS development version (unstable)
-------------------------------------------------------

The latest develop version of SOMANET OS is accessible also on the **develop** branch at the repository. It is not recommended for most of the users to use this SOMANET OS version since it is susceptible of contain unstable pieces of software. To access the develop branch and execute:

:code:`git checkout develop`

If you receive the "*warning: unable to rmdir sc\_sncn\_motorctrl\_sin: Directory not empty*", please remove the *sc\_sncn\_motorctrl\_sin* repository manually:

:code:`rm -r -f sc\_sncn\_motorctrl\_sin`

Initialize submodules that are not part of the master branch:

:code:`git submodule init`

Update submodules to get the actual pointed commit:

:code:`git submodule update`
                    
