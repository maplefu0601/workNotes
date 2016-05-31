
## login to centerOS vm
	1. open terminal
	2. ssh genesys@135.39.46.50	(using password genesys)
	3. run gws_......start/stop.....
	
## How to setup Dashboard and run it
	1. checkout the code using hg command
	* hg clone --verbose http://hg-gws.us.int.genesyslab.com/gws "C:\work\gws"
	2. build front code
	* cd c:\work\gws\cloud-server\dashboard
	..2. npm install grunt
	..3. npm install
	3. build back-end code
	..1. grunt default
	..2. grunt default watch
	..3. grunt test --with-coverage
	
  
1. First ordered list item
2. Another item
⋅⋅* Unordered sub-list. 
1. Actual numbers don't matter, just that it's a number
⋅⋅1. Ordered sub-list
4. And another item.

⋅⋅⋅You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).

⋅⋅⋅To have a line break without a paragraph, you will need to use two trailing spaces.⋅⋅
⋅⋅⋅Note that this line is separate, but within the same paragraph.⋅⋅
⋅⋅⋅(This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)

* Unordered list can use asterisks
- Or minuses
+ Or pluses
+ 
