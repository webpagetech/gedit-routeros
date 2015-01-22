# **gedit-routeros**
Mikrotik RouterOS code syntax highlighting for .rsc Files

## **Installation:**

1. Get the src files
  * download the *gedit-routeros-master.zip* file from github
2. Unzip the src files
  * unzip the file so that the zip file within it (*gedit-routeros.zip*) is within your ~/Downloads Folder
    * *cd ~/Downloads && unzip gedit-routeros-master.zip*
3. Open a *root* terminal
  * open a terminal
  * *su root* or *sudo -s* to gain root access
4. Copy *gedit-routeros.zip* to Gedit's usr share folder
  * *cp ~/Downloads/gedit-routeros.zip /usr/share/gtksourceview-3.0/*
5. cd to Gedit's usr share folder
  * cd /usr/share/gtksourceview-3.0/
6. Move the .xml style file into Gedit's language-specs/ folder and move the .lang sytax file into Gedit's styles/ folder.
  * unzip gedit-routeros.zip


## **Notes:**

* That should insert the mikrotik.lang file into /usr/share/gtksourceview-3.0/language-specs/mikrotik.lang

* It should also insert the routerosv6.xml file to /usr/share/gtksourceview-3.0/styles/routerosv6.xml

* Both files should have permitions root:root 644

* You can manualy place these files in there folders rather than using the zip file *gedit-routeros.zip*

* open up gedit

* any files with the .rsc extention should have there sytax highlighted

* you can force it by going to view->highlight Mode... and select RouterOSv6 for none .rsc files that you want routeros highlighting for.

* you can also use the routerOS syle by going to edit->preferances->fonts&colors and selecting *RouterOSv6*. 
