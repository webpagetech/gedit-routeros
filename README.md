# gedit-routeros    ###### Patches and improvements welcome!

Mikrotik RouterOS <br /> Syntax Highlighting <br /> For <br /> RouterOS .rsc Files | ![Web Page Tech](https://avatars3.githubusercontent.com/u/10645972?v=3&s=200)
:---: | :---:
Tested in: <br /> Ubuntu 12.04 <br /> Ubuntu 14.04 | [Project Home Page](http://webpagetech.com/index.php/en/tutorials/mikrotik-tutorials/40-mikrotik-gedit)<br />[_github_ Home](https://github.com/webpagetech/gedit-routeros)

### Easy Installation:

Clone and execute the install.sh script.

### Installation:

1. Get the src files
    * Download the __gedit-routeros-master.zip__ file from [GitHub](https://github.com/webpagetech/gedit-routeros/archive/master.zip) <br />into your ~/Downloads Folder.

2. Unzip the src files
  * unzip __gedit-routeros-master.zip__ into your ~/Downloads Folder

    * `unzip ~/Downloads/gedit-routeros-master.zip -d ~/Downloads/`

3. Move the .xml style file into the _gedit_ __styles/__  folder <br /> and <br /> move the .lang syntax file into the _gedit_ __language-specs/__ folder.

  * `cd ~/Downloads/gedit-routeros-master/ && ./install.sh`

#### Note:

* You can manualy place these files in there folders rather than using the __install.sh__ script
  * Insert the mikrotik.lang file into __~/.local/share/gtksourceview-3.0/language-specs/mikrotik.lang__
  * Insert the routerosv6.xml file to __~/.local/share/gtksourceview-3.0/styles/routerosv6.xml__

#### Usage:

* Open up _gedit_
* Any files with the __.rsc__ extention should have RouterOS syntax highlighing
* You can force RouterOS syntax highlighing by going to __view->highlight Mode...__ and selecting __RouterOSv6__ for _none .rsc_ files that you want RouterOS highlighting for.
* You can also use the RouterOS style by going to __edit->preferances->fonts&colors__ and selecting __RouterOSv6__. 
