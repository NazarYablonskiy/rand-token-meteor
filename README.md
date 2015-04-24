# rand-token for MeteorJS
Generate random tokens from your choice of randomness.
https://www.npmjs.com/package/rand-token

## Instalation
```
meteor add nyablonskiy:rand-token
```

## Usage
```
// Generate a 16 character alpha-numeric token:
var token = RandToken.generate(16);

// Use it as a replacement for uid:
var token = RandToken.uid(16);

// Generate mostly sequential tokens:
var token = RandToken.suid(16);
```