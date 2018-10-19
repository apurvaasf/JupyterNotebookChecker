# JupyterNotebookChecker
## Motivation:
This is python script to automate running of a Jupyter Notebook. This is in order to help professors, such that they don't have to run the notebooks on their own. 
They feed in the URL of the notebooks and the data URL, if there is any, and the script runs and saves the notebook after running in a folder. Thus saving the professor time and energy.  

## Description
For each problem proposal, it does the following:
1. Makes a folder with specified name
2. Downloads notebook from the URL
3. Downloads datafile
4. Executes notebook
5. Saves the exceuted notebook back into the folder created in step 1.
