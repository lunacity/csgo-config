# csgo-config

Step 1:
Go To
F:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\csgo\cfg

Step 2:
Copy + Paste config.cfg, it should be config.cfg(1)
rename it to autoexec.cfg

Step 3:
Copy + Paste config.cfg, it should be config.cfg(1)
rename it to config_backup.cfg

Step 3:
Right click autoexec.cfg, edit with notepad++
Ctrl + A, delete entire contents
Paste in github code
Save autoexec.cfg

Step 4:
Right click config.cfg, edit with notepad++
Ctrl + A, delete entire contents
Save config.cfg

Step 5:
Right click config.cfg, go to properties
Check the read-only box at the bottom

Step 6:
Go to steam -> library
right click on csgo and goto properties
click launch options and add: +exec autoexec.cfg

Note: During launch if console is saying: 
'Config file cfg/config.cfg is read-only!!'
this is good, your autoexec.cfg settings are not being overwritten