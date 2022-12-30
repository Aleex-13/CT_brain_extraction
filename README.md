# CT_brain_extraction
Script to automatically extract the brain from non-contrast CT scans (3D) using 3D Slicer and the jupyter notebook extension.


How to use it:

1) Install 3D Slicer and the following extensions from the 3D Slicer extension manager 
    - SlicerJupyter (https://github.com/Slicer/SlicerJupyter)
    - SurfaceWrapSolidify (https://github.com/sebastianandress/Slicer-SurfaceWrapSolidify)

2) I wanted to use Slicer's Python kernel in an external Python environment. 

Doing so requires the following packages installed in your python environment:

    jupyter jupyterlab ipywidgets pandas ipyevents ipycanvas

Then open slicer, search in the Modules for the JupyterKernel and switch to module. In the section "Jupyter server in external Python environment" copy the command and run it in your python environment to install the kernel.

Alternatively you can also start a Jypter server in Slicer Python environment in the module and work there.

3) Open the notebook with jupyter and set the absolute paths to the input and output directories. (For me only absolute paths worked)
    - input must be dicom
    - output is saved as .nrrd

4) Select the Slicer Kernel and run the notebook.

