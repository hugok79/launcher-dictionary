# Launcher-Dictionary

Module based on Spellcheck plugin for Launcher module.

Spellcheck module inspired me to create this module. The main goal is to have a quick access to dictionary via Launcher module in Bodhi GNU/Linux.


<p align="center">
  <img src="http://www.enlightenment.org/ss/e-5c546dd0973cc5.02130478.png" alt="Screen Shot">
</p>


# Dependecies

* [EFL](https://www.enlightenment.org/download)
* [Moksha](https://github.com/JeffHoogland/moksha)
* [sdcv](https://wiki.archlinux.org/index.php/Sdcv)
* [stardict dictionaries](https://sites.google.com/site/gtonguedict/home/stardict-dictionaries)

This module depends on sdcv utility. It is a console Stardict application.

sdcv installing:
sudo apt-get install sdcv

Unpack downloaded dicts and copy to /usr/share/stardict/dic directory

# Usage

First one must load the module. Now assuming one has sdcv installed and an stardict dictionary, then usage should be as simple as opening Mokshas Quick Launcher and typing 'd ' without the single quote marks. Note: one must type the blank following the d. The prompt will change to a colon and now type a word that should be translated. A list as pictured above will be displayed.

# Module authors:

Full credit for the original code of this module go the enlightenment developers:
* Gustavo Barbieri
* Hannes Janetzek

Dictionary part
Štefan Uram a.k.a the_waiter <Bodhi Linux developer> 2019

Enjoy :)
