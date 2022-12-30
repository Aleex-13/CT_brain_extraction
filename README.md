# CT_brain_extraction
Script to automatically extract the brain from non-contrast CT scans (3D) using 3D Slicer and the jupyter notebook extension.


How to use it:

1) Install 3D Slicer and the SlicerJupyter extension from the 3D Slicer extension manager (see github repository here: https://github.com/Slicer/SlicerJupyter)

2) I wanted to use Slicer's Python kernel in an external Python environment. 

Doing so requires the following packages installed in your python environment:

    jupyter jupyterlab ipywidgets pandas ipyevents ipycanvas

Then open slicer, search in the Modules for the JupyterKernel and switch to module. In the section "Jupyter server in external Python environment" copy the command and run it in your python environment to install the kernel.

Alternatively you can also start a Jypter server in Slicer Python environment in the module and work there.

3) Start jupyter notebook in your python environment and select the slicer kernel to run the notebook. Set your input and output pahts in the notebook.




