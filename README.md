GTALUG's Code of Conduct
========================

Generate the Code of Conduct
----------------------------

I am generating the bylaws with [Pandoc](http://johnmacfarlane.net/pandoc/).

### HTML

	pandoc -N -c gtalug.css Code-of-Conduct/*.markdown -o GTALUG-Code-of-Conduct.html

### PDF

	pandoc -N -c gtalug.css Code-of-Conduct/*.markdown -o GTALUG-Code-of-Conduct.pdf
