You may use RAMP as an App in your pc. (Once RAMP's Executable file is created, you may use this App without python installed)
You only once need to bundle all files from this folder into .exe file, which is very simple. Here under are the steps.

1. Download all file from this folder named 'RAMP_GUI_Local_App' and save that folder somewhere into a local drive in your PC.(not system drive)
2. Open that folder. Press shift key(keep pressed) and Right click anywhere. Click on 'OpenPowerShell window here'
3. Write command 'pip install pyinstaller' . That will install Pyinstaller.
4. Now write command 'pyinstaller --onefile RAMP.py' (This command will convert your python file into executable .exe file)

You may also add thumbnail icon separately for RAMP.exe using command 'pyinstaller --onefile --icon=your_icon_name.ico RAMP.py' 

Once you run this, A folder named 'dist' will be created. inside that folder you may find your RAMP.exe file. You may use this file as an app. Now you may use this without python and even on another PC.
You may watch video on how to use RAMP_GUI here https://drive.google.com/file/d/1CZ8g5DOgo2e4h3vLrdSVpGt-KVbYaEVt/view 

Note : This standalone .exe file may show you virus threat when you Run or you try to upload or download it from the Online Drives. 
Please ignore it, it is a false positive detection as it has been compiled using all libraries and mosules, and .exe file do not have code signing certificate yet. 
You may for instance turn off the virus protection and after downloading or copy paste you may again turn on Virus protection. 
If your organisation have settings to not allow this, you may not be able to open it or download it or run it.
