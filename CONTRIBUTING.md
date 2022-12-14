# Contribution Guide

In the following document, you'll learn about the procedure of contributing to Jabir Technologies artwork. This document contains our policies and guidelines as well as a guide of registering your candidate artwork.

## Artwork policies

1. Since all products of _Jabir Technologies_ are being used by people of all ages, all artworks should NOT contain any form of _Not Suitable For Work_ content, which contains everything regarding nudity, alcohol or drug usage, graphic and gore imagery, etc.
2. Artworks should NOT infringe any copyrights or violate IP's (as in intellectual property) in any form, otherwise they won't be accepted by us.
3. We do not force you to use specific tools to create artwork, but FLOSS tools (such as InkScape or GIMP) are always appreciated and encouraged. 
4. A color palette will be provided further in this document for designer concerns.

### AI generated material

Since _Jabir Technologies_ is always open to innovating and pioneering technologies, there is no restrictions against AI generated material as long as they are not in violation of our policies. 

## How to contirbute

### Color Palette

![palette](palette.jpg)

### How to register an artwork

* First, fork this repository into your own github account.
* Then, clone it to your local computer. `git clone https://github.com/<YOUR-USERNAME>/artwork` 
* Create a branch
    * If you want to create a logo, create the branch like this `git checkout -b <YOUR-USERNAME>-logo`
    * If you want to create a wallpaper, create the branch like this `git checkout -b <YOUR-USERNAME>-wallpaper`
    * If you want to create a theme, create the branch like this `git checkout -b <YOUR-USERNAME>-theme`
        * Currently, we haven't decided for the desktop environment of choice, so please be aware that your themes might not be released in official release channels in the future.
    * If you want to create an icon theme, create the branch like this `git checkout -b <YOUR-USERNAME>-icon`
* Put your creations in respective folders.
    * If it's a logo, put it in `logos`. 
    * If it's a wallpaper, put it in `wallpapers`
    * If it's a theme, put the __theme folder__ in `themes`
    * If it's an icon theme, put the __icon theme folder__ in `icons`
* Make a pull request

## The Approval 

_Jabir Technologies_ will review your pull requests. Every accepted logo, wallpaper, icon set or theme, will be merged with the `main` branch and it'll be used in further products. 