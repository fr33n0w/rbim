# rbim
Reticulum Burning Inbox Messanger v1.0

One time burning inbox with GUI, 
based on the original example_receiver.py by markqvist (https://github.com/markqvist/LXMF/blob/master/docs/example_receiver.py) , edited and adapted, refactored in tkinter GUI.
-------------------------------------------------------------
DESCRIPTION:
This script generates a one time temporary identity and create a LXMF peer with personalised name that can be reached (messaged!) via Sideband, Nomadnet or MeshChat for Reticulum Network, or any other LXMF based messenger.
Messages can only be received, showing details on the sender hash addres and timestamp. Edit the code to include more details, like stamp cost, ratchet info, lxmf destination and more.
When you burn (close) it, you loose the created identity.
------------------------------------------------------------
PURPOSE of this script:
Do you know TempMails or Burning Phones? Same concept, but under Reticulum encryption!
If you are James Bond, you need it! :)

---------------------------------------------------------------

INSTALLATION REQUIREMENTS:

RETICULUM PACKAGES
pip install rns lxmf

TKINTER PYTHON MODULE:

Tkinter isn't distributed through pip; if it didn't come pre-packaged with Python, you have to get it from elsewhere:

    Ubuntu

sudo apt-get install python3-tk 

    Fedora

sudo dnf install python3-tkinter

    MacOS

brew install python-tk

-----------------------------------------------------------------

RUNNING THE SCRIPT:
python rbim.py
(or python3 rbim.py , based on your system)

SCREENSHOT:
![RBIM](https://github.com/user-attachments/assets/7c7e49f6-40a1-4399-a98f-ff5378f5e589)



