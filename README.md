**EODS-F23:** Elements of Data Science, Fall 2023

**Slides**

For the slides I use jupyter notebook with the RISE extension installed: https://rise.readthedocs.io/en/stable/ \
Image paths are then relative to the notebook folder (./images/*) \
When presenting, I'll use the RISE presentation mode so that I can edit and run python from the slide deck during class

To generate the pdf slides I use decktape: https://github.com/astefanutti/decktape \
For example, to convert week13 run:

`$(npm bin)/decktape rise -s 1920x1080 http://localhost:8888/notebooks/eods-f23/notebooks/eods-week13-databases_and_review.ipynb?token=2ba28d6c8a644cc785a0a25cf88fe5181f451ce1b59dfe66 slides_pdf/eods-week13-databases_and_review.pdf`

Note that token= needs to be the current token for the jupyter server (can get from either the log or right click on Jupyter image on the file-tree page and copy link)
