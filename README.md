grc.rsync.config
================

rsync.config for Generic Colouriser (grc)

Description
-----------

colorize rsyncs' change summary:

* deleted file: red
* new file: green
* changed file: yellow

Requirements
------------

grc

Usage
-----

$ grc --config="grc.rsync.config" | rsync --itemize-changes ...
