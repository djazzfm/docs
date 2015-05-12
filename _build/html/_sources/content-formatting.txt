
Content formatting
==================

Formatter
---------

- encode : from html to formatted content
- decode : from formatted content to html


Post processing
---------------

Html filtering : convert some text sequences to html, like bbcode.

Some example :

- smiley :
  
  - :) => <img src="smileys/smile.png">
  - :happy: => <img src="smileys/smile.png">
  - :( => <img src="smileys/sad.png">

- links :
  
  - [http://example.org/page.html](ma page.html) : <a href="http://example.org/page.html">ma page.html</a>
  - [wiki:path/to/wikipage](ma page wiki) : <a href="/wiki/path/to/wikipage">ma page wiki</a>

- images : [img src="img.png" width="100px" height="100px"] : <img src="img.png" width="100px" height="100px">
- etc ...
