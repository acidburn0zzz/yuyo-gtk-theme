Yuyo GTK Theme
================

Yuyo is an GTK3 theme belonging to the [Ubuntu MATE](http://www.ubuntu-mate.org/) project, it is a fork of the Orchis GTK theme from [Moka Project](http://mokaproject.com/).

Yuyo GTK Theme is distributed under the terms the GNU GPL v.3

###Preamble

If you find any bugs or issues with Yuyo or if you have a question, you can visit Yuyo's primary issue tracker on [GitHub](https://github.com/snwh/yuyo-gtk-theme/issues).


###Getting the Source

The source for Yuyo GTK3 Theme can be found [here](https://github.com/snwh/yuyo-gtk-theme).

Alternatively, you can clone the latest version its git repository:

    git clone https://github.com/snwh/yuyo-gtk-theme.git

###Using the Source

There are scripts to simplify the rendering process;to run them (and edit icons) you will need:

 * inkscape
 * python3

To render new assets from their source SVG files, either run the following:

    ./render-gtk3-assets.py
    ./render-gtk3-assets-hidpi.py
    ./render-metacity-assets.py
    ./render-unity-assets.py

Other asset sources are hidden a bit deeper. For borders:

    cd src/ 
    ./render-borders.sh

And GTK2 assets: 

    cd src/gtk2
    ./render-bits.sh

If it's throwing an error, the script may not be executable, try:
	
	chmod +x *

This script will look in the source directories (../src/*) and render the respective icons (provided there are changes).

-----------