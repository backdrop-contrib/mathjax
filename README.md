Mathjax for Backdrop CMS
------------------------

This module integrates the MathJax library into your Backdrop site. MathJax is the
modern JavaScript-based LaTeX rendering solution for the Internet.

Installation
------------

Using the MathJax CDN (recommended)
-------------------------------

1. Install and enable this module.

2. Add the MathJax filter to an existing or new text format under 
   Administration >> Configuration >> Text Formats. Put the MathJax filter at
   the bottom of the "Filter processing order".

3. Test it by adding a LaTeX formula between '$' in any node body (for example: 
   $2 + 2 = 4$). Select the body text format you configured on the Text Formats
   administration screen.


Using a local copy of MathJax (relies on libraries module)
----------------------------------------------------------

1. Install and enable this module.

2. Install and enable "libraries". See https://github.com/backdrop-contrib/libraries.

3. Install the third-party MathJax software:
     Download MathJax source from the MathJax website.
     Un-archive it into your "libraries" directory.
     You may need to create the "libraries" directory first.
     Rename it to "mathjax" (lower case).

Issues
------

None

Current Maintainer
------------------

Roberto Scalas (https://github.com/rscalas/)

Original Author
---------------
Module written by Thomas Julou.

http://drupal.org/user/273952

Credits
-------
MathJax: https://www.mathjax.org

2013: cilefen https://drupal.org/u/cilefen

2014: P. Magunia (pmagunia) https://www.drupal.org/u/pmagunia

License
-------
This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.
