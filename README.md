# color_code

A quick syntax file for taking color coded notes in sublime text, compatible with all your favorite color schemes out of the box.

Now with syntax highlighting in embedded code blocks for various common languages!

# Current highlights:

code blocks from common languages (python, java, c++, etc)
` ```python
...
``` `

in-line double quotes
`" ... "`

block double quotes
`"* ... 
...
... *"`

c-style end-of-line comments
`// ...`

c-style block comments
`/* ...
...
... */`

python-style end-of-line comments
`# ...`

this weird style of block comments that I *really* wish python had
`#* ...
...
... *#`

end-of-line emergencies
`!! ...`

block emergencies
`!* ...
...
... *!`

ALL CAPS (including numbers and underscores),

Proper Nouns (including numbers and underscores),

digits outside of caps and nouns,

math symbols and punctuation,

a reasonably functional version of url links,

and a few other random small things that I forgot!

# Requirements

Written with Sublime Text Build 4121. I believe at least Build 4075 is required.

You probably need to install [Package Control](https://packagecontrol.io/installation). And maybe also [PackageDev](https://github.com/SublimeText/PackageDev)?

# Installation

Download to the folder user defined packages.
#### windows
clone repo into: ``C:\Users\%USERNAME%\AppData\Roaming\Sublime Text 3\Packages\User\``
#### linux
clone repo into: ``/home/%USERNAME%/.config/sublime-text/Packages/User/``
#### mac
clone repo into: ``%i have no idea how macs work%/Packages/User/``

# To Do

Add support for more languages in embedded code blocks.

Add support for installation through Package Control.