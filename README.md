# fedroa-livecd
OVERVIEW
========
This project has a working sample of useful tools to build a live Fedora 23 distro using the latest versions of kernel and software, for those of you who buy the latest hardware, but can't get the standard distro to work.

This build as mentioned will include the latest F23 kernels, development tools, office, web, Google Chrome, mate and gnome, kdm login manager (since they have cooler screens), web server and mariadb (MySQL for those still not in the know) and some other useful tools like gparted.

REQUIREMENTS
============
I build this on Fedora using the following requirements:
* livecd-tools
* spin-kickstarts

USAGE
=====
Simply modify the fedora-live-base.ks and fedora-repo.ks files to include, exclude software packages and repoitories.  By default this build includes the rpmfusion repositories for free and non-free, due to some of the packages being installed.
