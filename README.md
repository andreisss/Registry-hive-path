***Registry Hives

Hives are the root directories in the registry structure. There are five root hives.
• HKEY_CLASSES_ROOT (HKCR) stores information about installed programs like file associations (associated programs for file
extensions), shortcuts for application. A copy of this hive is found under HKEY_CURRENT_USER\Software\Classes and HKEY_LOCAL_MACHINE\Software\Classes.

• HKEY_LOCAL_MACHINE (HKLM) stores information that is
common to all users on the system. It includes information related to hardware as well as software settings of the system.

• HKEY_USERS (HKU) this hive contains Windows group policy settings. 
A copy of this hive is also present under HKLM\SOFTWARE\ Microsoft\Windows NT\CurrentVersion\ProfileList\

• HKEY_CURRENT_CONFIG (HKCC) this hive contains the hardware profile that the system uses at startup.

• HKEY_CURRENT_USER (HKCU) this hive contains the information
of the currently logged-in user. This hive is also stored on the disk at
the location %UserProfile%\ntuser.dat, where the UserProfile is
the home directory of the currently logged-in user. You can obtain/ print the value of UserProfile by typing the command listed in


Path: C:\Windows\System32\config

![image description](https://i.ibb.co/hsRsnYC/registry-hive.png)

