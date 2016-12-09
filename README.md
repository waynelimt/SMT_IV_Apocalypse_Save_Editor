# SMT_IV_Apocalypse_Save_Editor
Save editor for Shin Megami Tensei IV - Apocalypse

This is a save editor for Shin Megami Tensei IV - Apocalypse, made in Python 3. Tested in Windows, most probably works in Ubuntu as well. Compatibility with Python 2 not tested though, feel free to test it. Note that this save editor is only tested working for the save slot 1 in-game (sdds4game1.sav), other slots are not tested. The skill descriptions are also copied from the save editor for SMT IV, so some of the skills may have changed.
<br/><br/>
Installation:
No installation needed for this. 

For Windows:
Just install Python 3 for Windows (https://www.python.org/downloads/, v3.5.2 at time of writing) with the default settings on. After that, you can just double click on the .py script and it should automatically launch the script with the installed python interpreter.


For Linux (Ubuntu):
Newer versions of Ubuntu (14.04 LTS & above) should come with Python 3 installed. Firstly, make the script executable, by typing the following in a terminal: chmod a+x <path to script>/smt_iv_apocalypse_save_editor.py

*Replace <path to script> with the path to the script itself.
After that, type in a terminal: ./smt_iv_apocalypse_save_editor.py

If there are no errors and the script successfully launches a GUI, then it is all good, you can ignore the following instructions.


However, Ubuntu 16.04 LTS does not have Tkinter package installed, which is responsible for the GUI for the script. So, if you are using Ubuntu 16.04 LTS, you will need to first install the Tkinter package by typing the following in a terminal: sudo apt-get install python3-tk

After installing the package, the script should launch properly.
