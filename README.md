yast-fonts
==========

[![Travis Build](https://travis-ci.org/yast/yast-fonts.svg?branch=master)](https://travis-ci.org/yast/yast-fonts)
<!---
No Jenkins worker is configured for this repository, disable the badge for now
[![Jenkins Build](http://img.shields.io/jenkins/s/https/ci.opensuse.org/yast-fonts-master.svg)](https://ci.opensuse.org/view/Yast/job/yast-fonts-master/)
-->

This YaST module brings a layer over fontconfig settings to control
font appearance on the system in two aspects: 
* font rendering algorithm type,
* font family preference.

The main mission is to bring font rendering options closer 
to user. It is intended to weaken term 'default font setting'.

Note: module is just developed, so it does not live in YaST 
namespace so far. For openSUSE 13.2 or later and Factory, please 
find packages in [home:pgajdos:font-setting](http://software.opensuse.org/package/yast2-fonts?search_term=yast2-fonts).

