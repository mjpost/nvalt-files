### nvALT configuration files

These templates began with templates
[published by Brett Terpstra](http://brettterpstra.com/2013/04/06/customizing-the-nvalt-preview/). I
modified them to remove evidence of the "Lopash" them and to add
support for [MathJAX](http://www.mathjax.org).

### What you'll get

* Support for [MathJAX](http://www.mathjax.org) in notes
* Automatic highlighting of code blocks with [highlight.js](http://softwaremaniacs.org/soft/highlight/en/)
* A basic implementation of [Widon't](http://shauninman.com/archive/2006/08/22/widont_wordpress_plugin) for headlines.
* Smooth scrolling when clicking footnotes and anchors.
* A "back to top" link that appears when scrolling down a note.

### Installation

1. First, back up any custom files you've created previously. 

   You can always restore the default just by deleting the
   `custom.css` and `template.html` files from
   `[User Home]/Library/Application Support/nvALT/`.

2. Copy the files in the zip folder to `[User Home]/Library/Application
Support/nvALT/`. 

   If the "nvALT" folder doesn't exist, create it or simply drag the
   folder you unzipped into **[User Home]→Library→Application
   Support**.

3. Download MathJAX and copy it to `mathjax`.

You should have the following files in your Support folder:

    custom.css
    highlight.pack.js
    jquery.min.js
    template.html
    mathjax/
      README.md
      MathJax.js
      ...
