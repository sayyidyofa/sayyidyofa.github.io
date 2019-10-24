---
layout: project
type: project
image: images/lemp-manager.png
title: LEMP Manager
permalink: projects/micromouse
# All dates must be YYYY-MM-DD format!
date: 2019-03-01
labels:
  - LEMP Stack
  - CLI
  - Python3
summary: I made a CLI-based LEMP Stack manager because I don't want to use XAMPP.
---
<img class="ui image" src="../images/lemp-manager.png" />


I use the subprocess module to manipulate statuses of services in LEMP Stack, that is Nginx, MariaDB (or maybe MySQL Server) and PHP (php-fpm), give it some nice terminal colors with third-party library: termcolor, ASCII welcoming text generator with pyfiglet, and then a loading animation with Halo.

The settings for LEMP Manager is stored as list in `config.py`

Here is the links of libraries I use:
[pyfiglet](https://pypi.org/project/pyfiglet/0.7/)
[Halo](https://pypi.org/project/halo/)
[termcolor](https://pypi.org/project/termcolor/)

You can look at it more at the [repo](https://github.com/sayyidyofa/lemp-manager-py).



