# IEEEAccessDrones

This repository is related to the paper "Design and validation of cyber-physical systems through co-simulation: the Voronoi Tessellation use case" submitted to the journal IEEEAccess.

The FMUS folder contains the FMUS necessary to run the co-simulations described in the paper.

The multi-models folder contains the configuration JSON to launch the co-simulation using the Maestro Application developed by the INTO-CPS Association (https://github.com/INTO-CPS-Association)

The file script_launch is a bash script that automatically:
  Downloads the Maestro Application from the INTO-CPS Association Github
  Executes a co-simulation using the FMUS and the multi-model of this GitHub

  Drones_cosimulation_run.ipynb is a Jupyter Notebook based on Python that simplifies the usage of this repository.
Considering that the material of this repository is based on a Unix-like OS, the notebook exploits Google Colab to run on a virtual machine hosted by Google.

The easiest way to use this tutorial is to run the Drones_cosimulation_run.ipynb notebook on Google Colab using the "Open in Colab" button at the top of the notebook.
The only requirement for the users is to have a Google Account.
Once in the Google Colab Environment the user should hit the command Runtime->execute All (shortcut Ctrl+F9) 
