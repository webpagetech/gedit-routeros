# gedit-routeros

Mikrotik RouterOS <br /> Syntax Highlighting <br /> For <br /> RouterOS .rsc Files | ![Web Page Tech](https://avatars3.githubusercontent.com/u/10645972?v=3&s=200)
:---: | :---:
Tested in: <br /> Ubuntu 12.04 <br /> Ubuntu 14.04 | [webpagetech.com](http://webpagetech.com)

### Installation:

1. Get the src files
    * Download the __gedit-routeros-master.zip__ file from [GitHub](https://github.com/webpagetech/gedit-routeros/archive/master.zip) <br />into your ~/Downloads Folder.

2. Unzip the src files
  * unzip __gedit-routeros-master.zip__ so that the zip file within it _(gedit-routeros.zip)_ unpacks into your ~/Downloads Folder

    * `unzip ~/Downloads/gedit-routeros-master.zip -d ~/Downloads/`

3. Move the .xml style file into the _gedit_ __styles/__  folder <br /> and <br /> move the .lang syntax file into the _gedit_ __language-specs/__ folder.

  * `sudo unzip ~/Downloads/gedit-routeros.zip -d /usr/share/gtksourceview-3.0/`

#### Notes:

* That should insert the mikrotik.lang file into __/usr/share/gtksourceview-3.0/language-specs/mikrotik.lang__
* It should also insert the routerosv6.xml file to __/usr/share/gtksourceview-3.0/styles/routerosv6.xml__
* Both files should have permissions: __root:root 644__
* You can manualy place these files in there folders rather than using the zip file __gedit-routeros.zip__

#### Usage:

* Open up _gedit_
* Any files with the __.rsc__ extention should have RouterOS syntax highlighing
* You can force RouterOS syntax highlighing by going to __view->highlight Mode...__ and selecting __RouterOSv6__ for _none .rsc_ files that you want RouterOS highlighting for.
* You can also use the RouterOS style by going to __edit->preferances->fonts&colors__ and selecting __RouterOSv6__. 
