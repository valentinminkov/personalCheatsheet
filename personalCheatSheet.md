# Cheatsheet Personal Notes 

*This is a living document that will be continuously updated with new information.*

## **Table of Contents**

- [Linux](#linux)
  - [KDE](#kde)
    - [Restarting Plasma in KDE](#restarting-plasma-in-kde)

---

# **Linux**

*Various Linux related information, tips and tricks.*

## **KDE**

*This section deals with the KDE desktop environment on Linux.*

### **Restarting Plasma in KDE**

1. Open a terminal window using `Ctrl + Alt + T`.
   
2. Enter the following command to kill the Plasma shell:
``` 
killall plasmashell
```
This command terminates the Plasma shell process.

Once the Plasma shell process is terminated, you can restart it by running the following command:

```
kstart5 plasmashell
```
