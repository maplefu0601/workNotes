
## login to centerOS vm
	1. open terminal
	2. ssh genesys@135.39.46.50	(using password genesys)
	3. run gws_......start/stop.....
	
## How to setup Dashboard and run it
1. checkout the code using hg command
	* hg clone --verbose http://hg-gws.us.int.genesyslab.com/gws "C:\work\gws"
2. build front code
	1. cd c:\work\gws\cloud-server\dashboard
	2. npm install grunt
	3. npm install
3. build back-end code
	- grunt default
	- grunt default watch
	- grunt test --with-coverage
	
## Generate API doc
	- grunt jsdoc
	- you will find the doc under folder docs\Dashboard API - Integration

## Install Sublime 3 package control
	1. Ctrl + ` to open console window
	2. import urllib.request,os,hashlib; h = '2915d1851351e5ee549c20394736b442' + '8bc59f460fa1548d1514676163dafc88'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by)
	-- or you could install it manually
	Manual
	
	If for some reason the console installation instructions do not work for you (such as having a proxy on your network), perform the following steps to manually install Package Control:
	
	1. Click the Preferences > Browse Packages… menu
	2. Browse up a folder and then into the Installed Packages/ folder
	3. Download Package Control.sublime-package and copy it into the Installed Packages/ directory
	4. Restart Sublime Text



	
	
