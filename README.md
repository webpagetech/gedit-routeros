# gedit-routeros

Mikrotik RouterOS code syntax highlighting for .rsc Files |  ![Web Page Tech](https://avatars3.githubusercontent.com/u/10645972?v=3&s=200)
:---: | :---:
tested only in ubuntu 14.04 | [webpagetech.com](http://webpagetech.com)

### Installation:

1. Get the src files
    * download the __gedit-routeros-master.zip__ file from [GitHub](https://github.com/webpagetech/gedit-routeros/archive/master.zip)
2. Unzip the src files
  * unzip __gedit-routeros-master.zip__ so that the zip file within it _(gedit-routeros.zip)_ unpacks into your ~/Downloads Folder
    * `unzip ~/Downloads/gedit-routeros-master.zip -d ~/Downloads/`
3. Move the .xml style file into Gedit's __styles/__  folder and move the .lang sytax file into Gedit's __language-specs/__ folder.
  * `sudo unzip ~/Downloads/gedit-routeros.zip -d /usr/share/gtksourceview-3.0/`

#### Notes:

* That should insert the mikrotik.lang file into __/usr/share/gtksourceview-3.0/language-specs/mikrotik.lang__
* It should also insert the routerosv6.xml file to __/usr/share/gtksourceview-3.0/styles/routerosv6.xml__
* Both files should have permissions: __root:root 644__
* You can manualy place these files in there folders rather than using the zip file __gedit-routeros.zip__

#### Usage:

* open up gedit
* any files with the .rsc extention should have RouterOS syntax highlighing
* you can force RouterOS syntax highlighing by going to __view->highlight Mode...__ and selecting __RouterOSv6__ for none .rsc files that you want RouterOS highlighting for.
* you can also use the routerOS style by going to __edit->preferances->fonts&colors__ and selecting __RouterOSv6__. 
