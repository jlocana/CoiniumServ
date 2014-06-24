![Screenshot](http://coinium.org/assets/images/logo/coinium-icon.png)
# CoiniumServ [![Build Status](https://travis-ci.org/CoiniumServ/CoiniumServ.svg?branch=develop)](https://travis-ci.org/CoiniumServ/CoiniumServ) [![Build status](https://ci.appveyor.com/api/projects/status/3x349ig9dt14943t)](https://ci.appveyor.com/project/raistlinthewiz/coiniumserv)
 
CoiniumServ is a high-performance pool-server implementation developed with C# that can host multiple pools together with their own wallet-daemon connections and ports. 

#### Info

* Website: http://www.coinium.org
* [Master Plan](https://github.com/CoiniumServ/CoiniumServ/wiki/Master-Plan)
* [FAQ](https://github.com/CoiniumServ/CoiniumServ/wiki/FAQ)
* [Documentation & Wiki](https://github.com/CoiniumServ/CoiniumServ/wiki/)

#### More
* IRC (**irc.freenode.net**):
  - **#coinium-serv** [user support](http://webchat.freenode.net/?channels=%23coinium-serv&prompt=1&uio=OT10cnVlde)
  - **#coinium-dev** [dev talk](http://webchat.freenode.net/?channels=%23coinium-dev&prompt=1&uio=OT10cnVlde)
  - **#coinium** [official pools](http://webchat.freenode.net/?channels=%23coinium&prompt=1&uio=OT10cnVlde)
* [Twitter](http://twitter.com/coinium)
* [Bitcointalk.org](https://bitcointalk.org/index.php?topic=604476.0)

### Features

##### Multiplexed Structure
* Multiple pools & ports.
* Multi-pool (switched) mining support.
* Multiple daemon connections.
* Multiple database layers.

##### Functionality
* Stratum server (over sockets) support. [in-development]
* Vanilla server (getwork & getblocktemplate over http server) support. [in-development]

##### Development Model
* Strictly [follows](https://github.com/CoiniumServ/CoiniumServ/tree/develop/src/Tests) the [Test Driven Development](http://en.wikipedia.org/wiki/Test-driven_development) model. We have implemented extensive tests for all important functionality and never merge in code that breaks tests and stuff. Yet again, when a new functionality is introduced we also expect proper tests to be implemented within the PR. In simple words, most probably you won't notice any functionality-breaking changes within the repository.
* A strict ruleset for the [Development Model](https://github.com/CoiniumServ/CoiniumServ/wiki/Development-Model). You can follow our bleeding-edge [Develop](https://github.com/CoiniumServ/CoiniumServ) branch or stay with-in the stable [Master](https://github.com/CoiniumServ/CoiniumServ/tree/master) branch.

* Coin wallet daemon rpc connection support.
   
### Motivation

For more information about the motivation behind CoiniumServ, check [Master Plan](https://github.com/CoiniumServ/CoiniumServ/wiki/Master-Plan).

### Requirements

* C# runtime (mono or dotnet)
* Coin daemon

### Building

* Check [Building & Running](https://github.com/CoiniumServ/CoiniumServ/wiki/Building-&-Running).

### Screenshots

![Screenshot](http://i.imgur.com/Pql7h0y.png)

### Developers

* [Developer's Guide](https://github.com/CoiniumServ/CoiniumServ/wiki/Developer's-Guide)
* [Technical Documentation](https://github.com/CoiniumServ/CoiniumServ/wiki/Technical-Documentation)

#### Continious Integration

Every build of CoiniumServ is built & tested;
* Mono: [travis](https://travis-ci.org/CoiniumServ/CoiniumServ).
* dotNet: [appveyor](https://ci.appveyor.com/project/raistlinthewiz/coiniumserv)
 
#### Bounties

BountySource integration available over [here](https://www.bountysource.com/trackers/401667-coiniumserv). You can set bounties and solve them.

[![Bountysource](https://api.bountysource.com/badge/team?team_id=760&style=bounties_received)](https://www.bountysource.com/teams/coinium/issues?utm_source=Coinium&utm_medium=shield&utm_campaign=TEAM_BADGE_1)

#### Tips

You can send tips and furher support the project or get tips for contributing by commiting.

[![tip for next commit](http://tip4commit.com/projects/760.svg)](http://tip4commit.com/projects/760)

### Donation

You can contribute the development of the project by donating; 

* BTC: `18qqrtR4xHujLKf9oqiCsjmwmH5vGpch4D`
* LTC: `LMXfRb3w8cMUBfqZb6RUkFTPaT6vbRozPa`
* DOGE: `D7mzHQtkWD9B1Xwnmjfg9x2DofbaZBg6Lc`

### License
Check the [License](https://github.com/CoiniumServ/CoiniumServ/blob/develop/LICENSE) file.
