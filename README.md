# Jupyter-NoteBook-Primer
This is a readme file describing commands for Jupter NB




- To Set default path in JupterNB
 - From StackOverflow - https://stackoverflow.com/questions/35254852/how-to-change-the-jupyter-start-up-folder
 -  jupyter notebook --generate-config
 -  C:\Users\username\.jupyter\jupyter_notebook_config.py.
 -  Open with text editor and replace #c.NotebookApp.notebook_dir = '' with c.NotebookApp.notebook_dir = '/the/path/to/home/folder/'
