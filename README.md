# gedit-routeros
##### Mikrotik RouterOS code syntax highlighting for .rsc Files

### Installation:

1. Get the src files
  1. download the __gedit-routeros-master.zip__ file from Github
2. Unzip the src files
  1. unzip the file so that the zip file within it _(gedit-routeros.zip)_ is within your ~/Downloads Folder
    * `cd ~/Downloads && unzip gedit-routeros-master.zip`
3. Open a __root__ terminal
  1. open a terminal
    * `su root`
      * or
    * `sudo -s`
      * to gain root access
4. Copy __gedit-routeros.zip__ to Gedit's usr share folder
  * `cp ~/Downloads/gedit-routeros.zip /usr/share/gtksourceview-3.0/`
5. cd to Gedit's usr share folder
  * `cd /usr/share/gtksourceview-3.0/`
6. Move the .xml style file into Gedit's __language-specs/__ folder and move the .lang sytax file into Gedit's __styles/__ folder.
  * `unzip gedit-routeros.zip`


#### Notes:

* That should insert the mikrotik.lang file into __/usr/share/gtksourceview-3.0/language-specs/mikrotik.lang__

* It should also insert the routerosv6.xml file to __/usr/share/gtksourceview-3.0/styles/routerosv6.xml__

* Both files should have permissions: __root:root 644__

* You can manualy place these files in there folders rather than using the zip file __gedit-routeros.zip__

#### Usage:

* open up gedit

* any files with the .rsc extention should have there syntax highlighing

* you can force syntax highlighing by going to __view->highlight Mode...__ and selecting __RouterOSv6__ for none .rsc files that you want RouterOS highlighting for.

* you can also use the routerOS syle by going to __edit->preferances->fonts&colors__ and selecting __RouterOSv6__. 
