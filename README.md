# Gizyk-stack

It's my stack with workflow automation for coding .psd to .html.

## The stack includes

* gulp
    * coverts sass to css.
    * automatically adds prefixes to css code.
    * minifys .css file.
    * reanames output file.
    * runs webpack to link .js files and minify them.
    * locates output files into dist directory.
    * runs local server with website and synchronises it everytime after save any file.
    * additionaly, when gulp finds any issue, it doesn't interrupt its work.
+ webpack
    * links .js files (also libs like jquery) into one.
    * minifys .js output file.
    * renames .js output file.