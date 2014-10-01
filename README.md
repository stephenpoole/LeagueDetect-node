LeagueDetect-node
=================

Tracks the game state of League of Legends using the game's log file.  
  
Example
=======
  
```
var leagueDetect = require('./main.js');
var opts = {path: 'E:\\Applications\\League of Legends'};
var ld = new leagueDetect(opts);

ld.events.on('LoadStart', function(evt) {
  console.log('Loading has started!');
});
```  
  
Events
======

LogStart  
LoadStart  
GameStart  
GameEnd  
LogEnd  
LoadConnectError  
ReplayConnectError  
ReplayEndGameError  
