*************************************
iMOD Suite installation instructions
*************************************

..
  Author comment:
  This index page is required for the imod-installer.pdf, 
  which provides 
  instructions for the msi on the imod download portal.
  https://download.deltares.nl/en/download/imod-viewer/


The iMOD Suite offers different modules which support modelling with MODFLOW 6
(including unstructured meshes):

* iMOD Viewer: The iMOD Viewer consist of a standalone 3D viewer and a QGIS
  plugin. The iMOD QGIS Plugin QGIS plugin allows visualisation of model input and
  output with tools for cross-sections, timeseries and link to the 3D viewer. It
  supports structured NetCDF, UGRID and IPF files. And the iMOD 3D Viewer for
  interactive 3D visualisation of unstructured input and output. Supports UGRID
  file format and IPF borelog files.

* iMOD Python: A Python package to support MODFLOW groundwater modeling. It makes
  it easy to go from your raw data to a fully defined MODFLOW model, with the aim
  to make this workflow reproducable.

* iMOD Coupler: Software that couples MODFLOW 6 to other computational cores. It
  currently supports a coupling to MetaSWAP, but additional computational cores
  are planned in the future.

  
The viewer setup, Deltaforge, and documentation can be downloaded from the 
`download portal <https://download.deltares.nl/en/download/imod-viewer/>`_.
After downloading, please unzip the iMOD zip file and install the MSI file as described in the instructions below.

A user guide for the iMOD Viewer can be found in the `online documentation 
<https://deltares.github.io/iMOD-Documentation/viewer_index.html>`_.

.. toctree::

   viewer_install_msi
   deltaforge_install
