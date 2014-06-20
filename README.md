navit-nuc-layout
================

My own Navit layout based upon android-mdpi

You will probably need the svg icons from : https://github.com/twain47/Open-SVG-Map-Icons

Navit currently expects all icons to be in xpm/ so you need to rename them:
$ for d in *; do for f in $d/*; do mv $f ${d}_`basename $f`; done; done

Then move all icons to navit-src/navit/xpm/ and run make
