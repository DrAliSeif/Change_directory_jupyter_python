# Change_directory_jupyter_python
Change directory jupyter python

# For windows
1. Press `Ctrl+R` 
2. Type `cmd` 
3. Type in comand window
```sh
jupyter notebook --generate-config
```
4. go to this directory `C:\Users\Ali\.jupyter` (note:Enter your user instead of Ali)
5. Open `jupyter_notebook_config.py` with Notepad
6. Press `Ctrl+F` 
7. Type in Find
```sh
c.NotebookApp.notebook_dir
```
8. In this `#c.NotebookApp.notebook_dir = ''`, I will change it to G: drive `c.NotebookApp.notebook_dir = 'g://'` . After the file is edited, save it in the same location. (note:Remove # and exist two Backslash[//])
