# gedit-routeros
Mikrotik RouterOS code syntax highlighting for .rsc Files

Installation:
1)
download the gedit-routeros-master.zip file from github
2)
unzip the file so that the zip file within it (gedit-routeros.zip) is within your ~/Downloads Folder
3)
open a terminal and su to root
4)
cp ~/Downloads/gedit-routeros.zip /usr/share/gtksourceview-3.0/
5)
cd to 
/usr/share/gtksourceview-3.0/
6)
unzip gedit-routeros.zip


###
-That should insert the mikrotik.lang file into /usr/share/gtksourceview-3.0/language-specs/mikrotik.lang
-It should also insert the routerosv6.xml file to /usr/share/gtksourceview-3.0/styles/routerosv6.xml
-Both files should have permitions root:root 644
-open up gedit
-any files with the .rsc extention should have there sytax highlighted
-you can force it by going to view->highlight Mode... and select RouterOSv6
-you can also use the router os syle by going to edit->preferances->fonts&colors and selecting RouterOS
