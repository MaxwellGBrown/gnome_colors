============
gnome_colors
============

This is my gnome terminal settings, done particularly so I can move around my custom colorscheme easily.

Export
------

To export the current gnome terminal settings...

::

  $ gconftool-2 --dump '/apps/gnome-terminal' > gnome-terminal-conf.xml


Import
------

To import the gnome terminal settings...

::

  $ gconftool-2 --load gnome-terminal-conf.xml

Note that this configuration overwrites **all** terminal settings.

To see the affected settings, run...

::

  $ gconftool-2 -R '/apps/gnome-terminal


=========
Resources
=========

`Stack overflow that inspired myself to do this <http://superuser.com/questions/241551/how-can-i-export-my-ubuntu-terminals-color-scheme-for-use-on-other-computers>`__

`How to load this file from a Git repo in Ubuntu >=15.04 <http://askubuntu.com/questions/668227/load-theme-files-in-gnome-terminal-on-ubuntu-15-04>`__
