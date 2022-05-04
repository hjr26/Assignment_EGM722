# Assignment for EGM 722 - Repository containing scripts to run an NDVI and NDMI on a Landsat Image.

The scripts, environment and gitignore are available for download in the main repository. 
There are two scripts (Jupyter Notebooks) which explain the code and theory behind it. 
You can download the environment.yml file and recreate the environment in your GUI of choice. This will automatically install the main dependencies which are "Glob", "Matplotlib", "Numpy" and "Tifffile".
Please note that "Earthpy" is also required to be installed and may not be present in some GUIs. You can install this from the command prompt within your environment using Pip Install Earthpy.
At this stage you can launch the Jupyter Notebooks and work through the scripts!
Both scripts use a Landsat 8 satellite image as an example walkthrough. This image needs to be stored in the same directory as the user’s environment in a folder called “Image”, although the user may customise this in the script should they desire it. The test image was captured over northwest Brazil from 2022, which can be accessed and downloaded free of charge from the USGS Earth Explorer. The test image’s code is “LC08_L1TP_229063_20211031_20211109_01_T1”, but the user can replace this with any Landsat image from Landsat 4, 5, 7 or 8 satellites. 

Enjoy!
