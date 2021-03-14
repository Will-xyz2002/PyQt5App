# PyQt5App
My learning records of PyQt5 GUI programming
## At the start
PATH problem:
1...After installation of the PyQt5, the Path should be added into the Environment variable. Or just install the PyQt5 in Pycharm which is much easier.
2...Add Qt designer and PyUIC to the external tools in Pycharm
3...Use designer.exe to set up the main window. And I should save the file in the path of the pycharm project (instead of save to the package in the subpath of the pycharm project)
4...Use UIC to transfer the .ui file to the .py file .
5...And create a new .py file to control the reference in the mainwindow
6. WILL ADD MORE WHILE I'M LEARNING......
--------------------
# some tips may be useful to you...
if your program runned successfully, but show less letters on the mainwindow, don't worry, just add
```
label.resize(400,40)
```
if your problems happen on label part, otherwise, change the 'label' to what you want.
