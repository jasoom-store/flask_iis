# Flask_IIS

- Enable and install WinRW
- install IIS
- Make project folder & venv & main file
- install wfastcgi
- do wfastcgi-enable -> to get path

- on IIS make a site
- on handeler map on site -> add module mapping
- *, FastCgiModule, the path, any name, requst: uncheck invoke

- FastCGI setting on user -> duble click on path
- (Collection) click on ...
- add -> PYTHONPATH, project path
- add -> WSCI_HANDLER, mainfile.var

<!-- Permitions -->
- site & python folders
- right click & click properties
- security -> edit -> add
- IUSR -> check names
- IIS_IUSRS -> check names
