# Look at this graph! 

DESCRIPTION:
	"Look at this graph!" - Nickelback
This package provides a useful alternative to \input (for tikz figures) and \includegraphics when displaying nice graphs. 


INSTALLATION:
1. Place this folder in /texlive/2019/texmf-dist/tex/latex/local/
2. In the terminal, type: 
	texhash
and press enter.
3. Enjoy looking at those graphs!


PACKAGE USAGE:
Required packages: graphicx, tikz

\lookatthisgraph{mytikzpicture}: The tikz figure defined in the file mytikzpicture.tex will be shown as Nickelback's graph.

\lookatthisgraphGFX{mypicture}: The picture in mypicture.extension (supports the same extensions as \includegraphics) will be shown as Nickelback's graph.

The size of Nickelback with the graph is always \textwidth.

