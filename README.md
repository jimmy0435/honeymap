HoneyMap
========

--------
Add "protocol" field to server daemon

Installation
------------
* apt-get install git golang mercurial make
* git clone https://github.com/fw42/honeymap
* In honeymap/server/
  * go get
  * go build
  * cp config.json.example config.json
  * edit config.json
* In honeymap/
  * On Ubuntu: apt-get install coffeescript
  * On Debian: Install node.js, then npm install coffeescript
  * make
* Run server/server
* Go to http://your-server:3000/
* Optionally, use nginx as reverse proxy
