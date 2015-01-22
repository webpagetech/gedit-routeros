# **gedit-routeros**
Mikrotik RouterOS code syntax highlighting for .rsc Files

### **Installation:**

1. Get the src files
  * download the __gedit-routeros-master.zip__ file from github
2. Unzip the src files
  * unzip the file so that the zip file within it _(gedit-routeros.zip)_ is within your ~/Downloads Folder
    * _cd ~/Downloads && unzip gedit-routeros-master.zip_
3. Open a *root* terminal
  * open a terminal
  * _su root_  or  _sudo -s_  to gain root access
4. Copy __gedit-routeros.zip__ to Gedit's usr share folder
  * _cp ~/Downloads/gedit-routeros.zip /usr/share/gtksourceview-3.0/_
5. cd to Gedit's usr share folder
  * cd /usr/share/gtksourceview-3.0/
6. Move the .xml style file into Gedit's __language-specs/__ folder and move the .lang sytax file into Gedit's __styles/__ folder.
  * _unzip gedit-routeros.zip_


#### **Notes:**

* That should insert the mikrotik.lang file into /usr/share/gtksourceview-3.0/language-specs/mikrotik.lang

* It should also insert the routerosv6.xml file to /usr/share/gtksourceview-3.0/styles/routerosv6.xml

* Both files should have permissions: _root:root 644_

* You can manualy place these files in there folders rather than using the zip file _gedit-routeros.zip_

* open up gedit

* any files with the .rsc extention should have there syntax highlighing

* you can force syntax highlighing by going to __view->highlight Mode...__ and selecting __RouterOSv6__ for none .rsc files that you want RouterOS highlighting for.

* you can also use the routerOS syle by going to __edit->preferances->fonts&colors__ and selecting __RouterOSv6__. 
