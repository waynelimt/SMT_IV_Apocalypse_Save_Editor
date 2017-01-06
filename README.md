# SMT_IV_Apocalypse_Save_Editor
Save editor for Shin Megami Tensei IV - Apocalypse (US Version)

This is a save editor for Shin Megami Tensei IV - Apocalypse, made in Python 3. Tested 100% working in Windows. Note that this save editor is only tested working for the save slot 1 in-game (sdds4game1.sav, the save for the cartridge slot 1, not the other slots for the SD card), other slots are not tested. The skill descriptions are also copied from the save editor for SMT IV, so some of the skills may have changed. If anyone has an updated list of the skills and their description, feel free to contact me and I will update the script.
<br/><br/><br/>
<b><i>Installation:</i></b>
No installation needed for this. 
<br/><br/>
<b><i>For Windows:</i></b>
Just install Python 3 for Windows (https://www.python.org/downloads/, v3.5.2 at time of writing) with the default settings on. After that, you can just double click on the .py script and it should automatically launch the script with the installed python interpreter.
<br/><br/>
<b><i>For Linux (Ubuntu):</i></b>
Newer versions of Ubuntu (14.04 LTS & above) should come with Python 3 installed. Firstly, make the script executable, by typing the following in a terminal: <b>chmod a+x <path to script>/smt_iv_apocalypse_save_editor.py</b>
<br/>
*Replace <path to script> with the path to the script itself.
After that, type in a terminal: <b>./smt_iv_apocalypse_save_editor.py</b>
<br/>
If there are no errors and the script successfully launches a GUI, then it is all good, you can ignore the following instructions.
<br/><br/>
However, Ubuntu 16.04 LTS does not have Tkinter package installed, which is responsible for the GUI for the script. So, if you are using Ubuntu 16.04 LTS, you will need to first install the Tkinter package by typing the following in a terminal: <b>sudo apt-get install python3-tk</b>
<br/>
After installing the package, the script should launch properly.
