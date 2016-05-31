
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
	
  

