# imgs2RISEslides

[![Binder](http://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fomightez/imgs2RISEslides/master?urlpath=lab/tree/index.ipynb)

Takes images and makes individual RISE slides from pairs of the images.

-------------------------------

[RISE](https://github.com/damianavila/RISE/) allows you to instantly turn your Jupyter Notebooks into a slideshow. No out-of-band conversion is needed, switch from jupyter notebook to a live reveal.js-based slideshow in a single keystroke, and back.

This repository simply makes it easier for you to convert several image files into slides for a RISE slideshow. You just upload them and kick off the script and it makes a Jupyer notebook file with pairs of the images as individual slides. Any odd one left after going through the list will be placed alone on the last slide of the notebook.

---- 

Related
-------

This [blog post by Mark Roepke](https://www.markroepke.me/posts/2019/06/05/tips-for-slideshows-in-jupyter.html) highlights and clearly illustrates the use of an extension that can allow cells to be side by side in a single row in a notebook and notes that, "When the notebook is then put into [RISE] presentation mode, the cells with stay in their columns giving two-column content on slides."

I have a repository that launches Binder sessions with Jupyter-RISE served via Binder with hide_code extension working [here](https://github.com/fomightez/jupyter-rise_with-hide_code). It allows toggling off of the code or output and it is respected in the notebook and corresponding slideshow.



Impetus
-------

Seemed a handy tool to have when contemplating making slides quick from images, and apparently [Rithika_Vaka](https://discourse.jupyter.org/t/jupyter-slides-how-do-i-have-a-function-that-creates-new-slides/3062) had a similar idea and need.



[![Binder](http://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fomightez/imgs2RISEslides/master?urlpath=lab/tree/index.ipynb)