# konqueror-throbber-icon
A drop-in throbber icon for Konqueror, for when your preferred icon theme is missing one (or you don't like it).


![konq throbber icon](/base/48x48/animations/process-idle-kde.png)

## Installation instructions

To use this throbber icon, you can either drop it directly into your currently used theme, or create a new theme based on your favorite theme and copy the directory `/base/` into your theme's `base` directory as well.

In a fedora linux system, the path to system icon themes is `/usr/share/icons/`, so you would copy the contents of `/base/` from this repository into:

    /usr/share/icons/YOUR_THEME_HERE/base/
    
Or:

    ~/.icons/YOUR_THEME_HERE/base
    
Some themes will have a different directory for animated icons, so check your theme's `index.theme` for the correct path to place them if not as mentioned above.
