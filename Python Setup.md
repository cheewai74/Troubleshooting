#### Annaconda:
1. Change Browser
1.1 jupyter notebook --generate-config
1.2 notepad path_file\jupyter_notebook_config.py (notepad C:\Users\USER\.jupyter\jupyter_notebook_config.py)
1.3 c.NotebookApp.browser = 'C:/Program Files/Google/Chrome/Application/chrome.exe %s'
For Firefox, 'C:/Program Files/Firefox Developer Edition/firefox.exe" %s'


The __init__.py files are required to make Python treat directories containing the file as packages. This prevents directories with a common name, such as string , unintentionally hiding valid modules that occur later on the module search path.
