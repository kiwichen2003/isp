# isp
OBJECTIVE 
=====================  
This package delivers algorithms for a camera pipeline, where the pipeline starts by reading the raw image and metadata information, and generating an output rgb image.

SECTIONS  
=====================  
Currently the package contains at least one algorithm for the following sections:  
=> Black level correction[e]  
=> Vignetting / lens shading correction[e]  
=> Bad pixel correction[e]  
=> Channel gain white balance[e]  
=> Bayer denoise[d]  
=> Demosaic[m]  
=> Demosaic artifact reduction [m]  
=> Color correction[e]  
=> Gamma[e]  
=> Chromatic aberration correction [m]  
=> Tone mapping[e]  
=> Memory color enhancement [m]  
=> Noise reduction[e]  
=> Sharpening[e]  
=> Distortion correction[e]  

where, [e], [m], and [d] denote currently algorithmically easy, moderate, or difficult, respectively.

In this package several raw images are given in the "images" folder. Some tables are given in the "tables" folder, and demo images are given in the "demo_images" folder.

INSTALLATION
======================  
Code is written in python3 and tested in mac. This link can help to install python3: https://stackoverflow.com/questions/24615005/how-to-install-numpy-for-python-3-3-5-on-mac-osx-10-9.  
Following packages need to be installed: numpy, scipy, matplotlib, pypng. The packages can be installed via "pip3 install packagename" command in the terminal. Once packages are installed run the main.py file by typing "python3 main.py" command in terminal.

* pip install pypng==0.0.18

COMMENTS  
========================  
Please leave your thoughts and comments: mushfiqulalam@gmail.com  

