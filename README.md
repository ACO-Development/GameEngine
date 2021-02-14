<p align="center">
  <a href="https://modd.io">
    <img src="https://i.ibb.co/8YH2cn5/small-gamehub-aco.png" width="400" alt="Taro Engine logo">
  </a>
</p>

## 2D HTML5 Multiplayer Game Engine.
ACO Game Engine provides users to make fully working games with no code.
[Discord](https://discord.gg/WxYpJThjKh) or support us on [Patreon](https://www.patreon.com/acofficial)

## Demo ##
[<img src="./assets/images/demo.png" width="390" alt="demo">]()

## What's included in the box
- Box2D Physics
- Netcode using UWS and LZ-string compression
- Inventory & item system
- Unit attributes (HP, Energy, etc)
- Weapon system (melee & projectile)
- Dialogues
- Shops
- Unit control (top-down WASD or platformer)
- Client-side predicted projectile + unit movement (optional)
- Basic AI
- Mobile controls
- and more!

## Node version
Node versions above [12](https://nodejs.org/download/release/v12.20.0/) are not currently supported due to a downstream dependency (clusterws)

## How to run a game server
Just go in and make a game.

To run the game server, execute the following command:
```
npm run server --game=<gameID>
```
*if the gameID argument is not provided, then the engine will use game.json stored in root directory instead.

Your game's Game ID can be found in your Game Engine's game's sandbox. Go to menu -> about.

<img src="./assets/images/gameid.png" width="600" alt="How to get game id">

## Quick start example - Run "Two Houses" locally

Install [Node 12](https://nodejs.org/download/release/v12.20.0/) and then...

```
git clone https://github.com/moddio/taro.git
cd taro
npm install
npm run server --game=5a7fd59b1014dc000eeec3dd
```

## Connecting to the game server
Visit http://localhost:2000 to start testing game.

Taro is completely free and open source under MIT license.

ACO Engine was originally forked from [Isogenic Game Engine](https://www.isogenicengine.com/) back in 2016
