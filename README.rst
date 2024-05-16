============
**RAMP_GUI**
============

RAMP_GUI can be used in a three way. Three folder can be found in RAMP_GUI dictionory.

**1. RAMP_GUI_Local_App :** 
An executable file of RAMP can be used as an app. (Once created python or no other depending software required)

**2. RAMP_GUI_Stanalone_file :**
In this directory, users can utilize RAMP GUI by simply running the RAMP.py file independently. This method allows for standalone usage without the need for external dependencies.

**3. RAMP_GUI_graphic_depended :**
Similar to the standalone file approach, RAMP GUI can be utilized in this directory. However, it requires the RAMP.ui file to be present in the same folder. Additionally, users can modify the GUI design using the .ui file by opening it in Qt Designer.

Detailed instructions for utilizing each individual RAMP_GUI variant can be found within their respective folders, provided in accompanying Read_me files.


Whichever way you use RAMP_GUI, The GUI is same. You may watch tutorial video on how to use RAMP.
https://drive.google.com/file/d/1CZ8g5DOgo2e4h3vLrdSVpGt-KVbYaEVt/view 


**Features**
--------

** TODO (Scope of further developement / correction)**
--------------------------------------------------------
- Allowing GUI input for the 24:00 time window, which is currently restricted. (Current GUI allows us to provide Time window from 00:00 to 23:59 (HH:MM), It does not allow 24:00. That one minutes needs to be offset by user)
- Each countries have different holidays, Implementing country-specific holiday selection options to accommodate varying holiday schedules.
- Addition of more features and functionalities to enhance user experience.

**Credits**
-------
- RAMP
- Bhavesh Soni
- Hochschule Nordhausen
- Qt
- PyQt5


.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`audreyr/cookiecutter-pypackage`: https://github.com/audreyr/cookiecutter-pypackage
