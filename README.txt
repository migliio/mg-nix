Table of Contents
_________________

1. Introduction
2. Repository structure
.. 1. Files and usage


1 Introduction
==============

  Welcome to my personal Nix repository! Here, I store various NixOS
  configuration files that cater to different needs. This repository
  serves as a convenient way for me to manage and organize my virtual
  machines using quickemu [1] and NixOS [2].

  Nix is a powerful package manager and a functional programming
  language that enables reproducible builds and declarative system
  configurations. NixOS, based on Nix, is a Linux distribution that
  embraces these principles, allowing for efficient management and
  customization of system configurations.


2 Repository structure
======================

  - `./machines': configuration files for different virtual machines.
  - `./scripts': additional scripts or utilities that assist with
    managing the virtual machines.
  - `./configs': minimal configuration files to speed up the machine
    setup.


2.1 Files and usage
~~~~~~~~~~~~~~~~~~~

  - `./machines/ctfbox.nix': this is the configuration I use to solve
    CTFs, mainly tailored for binary analysis, reverse engineering, user
    and kernel exploitation.



Footnotes
_________

[1] <https://github.com/quickemu-project/quickemu>

[2] <https://nixos.org/>
