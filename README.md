# raspberry-pi-startscript
Create this script in /lib/systemd/system/"""your script name""".service

To start the script:  
```
sudo systemctl start your_script.service  
```
  
  
To check the status of the script:  
```
sudo systemctl start your_script.service
```

To make the script run after booting:
```
sudo systemctl enable your_script.service
```

To disable the script from running after booting:
```
sudo systemctl disable your_script.service
```
