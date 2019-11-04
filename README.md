# Look at this graph! 

## Description:
[Look at this graph!](https://www.youtube.com/watch?v=sIlNIVXpIns) - Nickelback

This LaTeX package provides a useful alternative to `\input` (for tikz figures) and `\includegraphics` (for non-tikz figures, e.g. png) when displaying nice graphs. 


## Installation:
1. Place this folder in `/texlive/2019/texmf-dist/tex/latex/local/` (or something similar if using e.g. MikTex)
2. In the terminal, type 
	`texhash`
and press enter.
3. Enjoy looking at those graphs!


## Package Usage & Notes:
*Required packages:* `graphicx`, `tikz`

 - `\lookatthisgraph{mytikzpicture}`: The tikz figure defined in the file `mytikzpicture.tex` will be shown as Nickelback's graph.

 - `\lookatthisgraphGFX{mypicture}`: The picture in `mypicture.extension` (supports the same extensions as `\includegraphics`) will be shown as Nickelback's graph.

 - Note: The size of Nickelback with the graph is always `\textwidth`.

 - See `example.pdf` for an example.

