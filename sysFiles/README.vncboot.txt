README for vncboot

The vncboot file launches tightvncserver at startup. 

Copy this file to the directory: /etc/init.d/
Make sure it has execute permissions: sudo chmod 755 /etc/init.d/vncboot

Add it to the startup by running the following:
sudo update-rc.d vncboot defaults

Remove from startup by running the following:
sudo update-rc.d -f vncboot remove