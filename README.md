# epi_image_analysis
Use the bash code to pull out the tif-files generated by the Lois lab epifluorescence microscope from the Pos0 folder. The Python code then enhances the contrast of the images using the skimage.equalize_adapthist function and performs color grading. It saves the images as 8-bit tif files with a Lookup Table (LUT) and a scale bar in a new folder.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lauraluebbert/epi_image_analysis.git/master?filepath=TEMPLATE_epi_image_analysis.ipynb)
