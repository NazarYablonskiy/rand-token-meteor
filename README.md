# rand-token for MeteorJS
Generate random tokens from your choice of randomness.
https://www.npmjs.com/package/rand-token

##Instalation
```
meteor add nyablonskiy:rand-token
```

##Usage
```
// Generate a 16 character alpha-numeric token:
var token = RandToken.generate(16);

// Use it as a replacement for uid:
var uid = require('rand-token').uid;
var token = uid(16);

// Generate mostly sequential tokens:
var suid = RandToken.suid;
var token = suid(16);
```