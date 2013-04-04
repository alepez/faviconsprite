faviconsprite
=============

Bash script. Given a list of domains, download favicons and create a single sprite with css rules.
The generated sprite is compatible with [bootstrap icons](http://twitter.github.com/bootstrap/base-css.html#icons)

Dependencies
------------

Needs `wget` `convert` and `montage` [ImageMagick](http://www.imagemagick.org).

Usage
-----

You have to provide a list of domains as parameters. The script outputs
two files: sprite.gif and sprite.css

    ./faviconsprite twitter.com facebook.com stackoverflow.com plus.google.com linkedin.com
 
### Output:    
`sprite.gif`, an image with all icons resized to 14x14 pixels.
`sprite.css`, a set of css rules with background offsets.
