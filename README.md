# Synthesizer V Professional PKGBUILD script for Arch Linux
This repo is used to make Synthv packages for Arch Linux because the AUR versions is too outdated.

(No, i will not make binary packages of it. You do it. )

## Content
    synthv            - PKGBUILD Script for building Synth V Professional
    svkey             - PKGBUILD Script for building YumeTool (may work?)
## Building Packages

Building SynthV package

    $ git clone https://github.com/kharovtobi/synthv-arch.git
    $ cd synthv
    $ makepkg -si
    
- YumeTool does not work when installed in /opt btw, go figure it out.
    
