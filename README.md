# Cheatsheet Personal Notes 

*This is a living document that will be continuously updated with new information.*

## **Table of Contents**

- [Linux](#linux)
  - [KDE](#kde)
    - [Restarting Plasma in KDE](#restarting-plasma-in-kde)
  - [Services](#services)
    - [Restarting Bluetooth Service](#restarting-bluetooth-service)

---

# **Linux**

*Various Linux related information, tips and tricks.*

## **KDE**

*This section deals with the KDE desktop environment on Linux.*

### **Restarting Plasma in KDE**

   
1. Enter the following command to kill the Plasma shell:
``` 
killall plasmashell
```

2. Restart it by running the following command:

```
kstart5 plasmashell
```

## **Services**

*This section deals with services on Linux.*

### **Restarting Bluetooth Service**


``` 
sudo systemctl restart bluetooth
```
