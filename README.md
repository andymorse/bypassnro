# Andy's Automated Bypass NRO

From the OOBE Screen press Shift + F10

```
curl -L fractionalit.io/bypass -o skip.cmd
skip.cmd
```

This will skip the entire OOBE process including microsoft account and ANY questions during the setup process.


autounattended.xml created with https://schneegans.de/windows/unattend-generator/. 

Need to customize Windows after install? Try: https://github.com/ChrisTitusTech/winutil
