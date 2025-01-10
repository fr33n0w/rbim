# rbim
Reticulum Burning Inbox Messanger v1.0

One time burning inbox, for command line or with GUI, 
based on the original example_receiver.py by markqvist (https://github.com/markqvist/LXMF/blob/master/docs/example_receiver.py) , edited and adapted, refactored in tkinter GUI.

-------------------------------------------------------------
DESCRIPTION:
This script generates a one time temporary identity and create a LXMF peer with personalised name that can be reached (messaged!) via Sideband, Nomadnet or MeshChat for Reticulum Network, or any other LXMF based messenger.
Messages can only be received, showing details on the sender hash addres and timestamp. Edit the code to include more details, like stamp cost, ratchet info, lxmf destination and more.
When you burn (close) it, you loose the created identity.
------------------------------------------------------------
PURPOSE of this script:
Do you know TempMails or Burning Phones? Same concept, but under Reticulum encryption!
Just a Proof Of Concept, but if you are James Bond, you need it! :)

---------------------------------------------------------------

INSTALLATION REQUIREMENTS:

For the terminal version, you need only RNS and LXMF.

For the GUI version you need RNS , LXMF , tkinter python module and an enviroment with $DISPLAY enabled (not working on headless systems, use terminal version for these machines).

--------------------------
GET RETICULUM PACKAGES:
pip install rns lxmf

-------------------------

TKINTER PYTHON MODULE for the GUI version only:

Tkinter isn't distributed through pip; if it didn't come pre-packaged with Python, you have to get it from elsewhere:

    Ubuntu

sudo apt-get install python3-tk 

    Fedora

sudo dnf install python3-tkinter

    MacOS

brew install python-tk

-----------------------------------------------------------------

DOWNLOADING THE SCRIPT:

(script with GUI): wget https://github.com/fr33n0w/rbim/releases/download/rbim/rbim_gui.py

(script without GUI, under terminal): https://github.com/fr33n0w/rbim/releases/download/rbim/rbim_term.py

-------------------------------

RUNNING THE SCRIPT:

(for the GUI script): python rbim_gui.py

(script without GUI): python rbim_term.py

(use python or python3 based on your system)

---------------------------------

SCREENSHOTS:

GUI:
![RBIM](https://github.com/user-attachments/assets/7c7e49f6-40a1-4399-a98f-ff5378f5e589)


Terminal version:
![RBIMterm](https://github.com/user-attachments/assets/32ed6a85-3c8d-496d-85b5-1a9d0a3c3185)


