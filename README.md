[![Node.js CI](https://github.com/SaturnMusic/PC/actions/workflows/main.yml/badge.svg)](https://github.com/SaturnMusic/PC/actions/workflows/main.yml)
<sup> | [download](https://nightly.link/SaturnMusic/PC/workflows/main/main?preview) </sup>

# FreeSaturn - Pc
## Freezer Reborn
### Your go-to **ToS Compliant** Custom Deezer Client

 For non-premium Deezer users.
(I've just removed premium account verification. Obviously premium features, as flac and 320kb qualities, doesn't work.)

### Donations
https://fund.saturn.kim/

# Featuring:
- [Listening Parties (Clubs)](https://clubs.saturn.kim)
- FLAC & MP3 320 support
- BYO Last.fm Integration (Safer solution!)
- Discord Listen Together & RPC
- Fixed homepage
- Minor updates to make things work with newer API
- Redundant importer removed
- (aaand don't forget everything the older app had)

### You can download Saturn right away although it is highly advised to build it yourself, customized to your own liking.

## Building

```
git clone https://github.com/joelmzj/FreeSaturn-Pc
git submodule init 
git submodule update
```

Requirements: NodeJS 17+  

You can build binary using npm script:
```
npm i 
npm run build
```

Or manually:

```
npm i
cd app
npm i 
```

Frontend:

```
cd client
npm i 
npm run build
cd ../..
```

Then you can run server-only using, default port: `10069`: 

```
cd app
node main.js
```

You can build binaries using:

```
npm run dist
```

# Links
- website: https://saturn.kim
- discord: https://discord.com/invite/fttYFSHPCQ
- telegram: https://t.me/SaturnReleases

# Download from Releases
https://github.com/SaturnMusic/PC/releases

# Mobile Version
https://github.com/SaturnMusic/mobile
