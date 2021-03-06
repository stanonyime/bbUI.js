## bbUI.js WebWorks Extension

When using [Context Menus](https://github.com/blackberry/bbUI.js/wiki/Context-Menus) for BlackBerry 10 you will need to include the WebWorks
extension contained in the **bbui** folder shown above in the file listing.

_**NOTE: This is only for BlackBerry 10 devices, and it is not needed for PlayBook BlackBerry 10 styling**_

### Installing the bbUI.js WebWorks Extension

Installing the bbUI.js extension in your WebWorks installation is quite simple.  You first locate your WebWorks installation directory.  On Windows the
default path is typically _C:\Program Files\Research In Motion\BlackBerry 10 WebWorks SDK a.b.c.d_

In this directory you will find a **Framework\ext** directory.  Simply copy and paste the **bbui** directory shown above into that ext directory.  It will end
up looking like the following:

```
Framework
   \ext
       \bbui
	      - client.js
		  - index.js
		  - manifext.json
```