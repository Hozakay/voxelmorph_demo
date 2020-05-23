Prepare voxelmorph demo
===============================

Anaconda is an easy way to handle versions, packages and modules in environments.
You can prepare it another way, but it will be easiest to go with conda.

a) Install Conda
----------------

Download and install Anaconda:
https://www.anaconda.com/distribution/#download-section
that contains all important Python packages.

Alternatively: If you have limited disk space install Miniconda:
https://docs.conda.io/en/latest/miniconda.html .

Select your Operating System under the section Regular installation on
https://conda.io/projects/conda/en/latest/user-guide/install/index.html
and follow the installation instructions on the web site.

b) Update Conda
---------------

Anaconda:

	'conda update anaconda'

Miniconda:

	'conda update conda'

will update your conda installation


c) Setup the voxelmorph environment
-----------------------------------

Creating an environment with the necessary packages specified in voxelmorph.yml:

	'conda env create -f voxelmorph.yml' 


d) Activate the environment
---------------------------

Activate the environment to work with it:

    'conda activate voxelmorph'

To deactivate an environment:

    'conda deactivate'


e) Run Jupyter Notebooks
------------------------

To run the demo in jupyter notebooks go to the Voxelmorph_demo folder and do:

  'jupyter notebook'
  
afterwards open voxelmorph.ipynb. You should be able to run the demo as you like.


e) Documentation
----------------

HowTo jupyter notebook:
https://jupyter-notebook.readthedocs.io/en/stable/notebook


For more information on Conda refer to the Conda Documentation:
https://conda.io/projects/conda/en/latest/index.html

For Jupyter:
https://jupyter.org/documentation



