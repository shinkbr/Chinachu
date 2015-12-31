![](https://yabumi.cc/14ecf8c4f119f2be2933bd85.svg)

# Chinachu Air

Most lovely Linux DVR Platform in Japan.
<https://chinachu.moe/>

[![npm version][npm-img]][npm-url]
[![Linux Build][travis-img]][travis-url]
[![Dependency Status][dep-img]][dep-url]
[![devDependency Status][devdep-img]][devdep-url]

[![tip for next commit][tip-img]][tip-url]

[Chinachu “Air” Release Information](https://github.com/kanreisa/Chinachu/wiki/Air)

## Features

* Completely New Real-time Web Universal App
* REST API Server
* CLI
* UPnP AV Server
* Multi [Mirakurun](https://github.com/kanreisa/Mirakurun) (Network Tuner) Support
* Multi Storage Support
* [Chinachu Cloud](https://cc.chinachu.moe/) Support

## Requirements

* Linux - x86 / x64
  - Debian / CentOS / Gentoo
  - sysvinit / OpenRC / systemd
* [Node.js](nodejs.org/) `>=4.1.1`
* [Mirakurun](https://github.com/kanreisa/Mirakurun)
* Chrome / Firefox / Edge

## Warnings

* **Don't** expose port 20772 on the internet, not even with NAPT.
* **Don't** share your Chinachu outside of your household.

## Install

```
sudo npm install -g --unsafe chinachu
```
This is all. Yes, magic.

* Web App will launched automatically. - go http:// _server-ipv4-local-addr_ :20772/

### Uninstall

```
sudo npm uninstall -g --unsafe chinachu
```

## CLI

### Administration

#### Config

```
chinachu config [server|operator|mirakuruns|ffmpeg]
```
Typically, don't need edit this.

* Also you can config on Web App.
* see: [docs/Configuration.md](docs/Configuration.md)

#### Log Stream

```
chinachu log [server|operator]
```

#### Service Management

```
chinachu [status|start|stop|restart]
```

## Contributing

[CONTRIBUTING.md](CONTRIBUTING.md)

## Slack Community

* Join: https://slack.chinachu.moe/
* Login: https://chinachu.slack.com/

## License

[Apache License, Version 2.0](LICENSE)

**Commercial License/Support** is provided by [Pixely LLC](https://pixely.jp/).

[npm-img]: https://img.shields.io/npm/v/chinachu.svg?style=flat-square
[npm-url]: https://npmjs.org/package/chinachu
[travis-img]: https://img.shields.io/travis/kanreisa/Chinachu.svg?style=flat-square
[travis-url]: https://travis-ci.org/kanreisa/Chinachu
[dep-img]: https://david-dm.org/kanreisa/Chinachu.svg?style=flat-square
[dep-url]: https://david-dm.org/kanreisa/Chinachu
[devdep-img]: https://david-dm.org/kanreisa/Chinachu/dev-status.svg?style=flat-square
[devdep-url]: https://david-dm.org/kanreisa/Chinachu#info=devDependencies
[tip-img]: http://tip4commit.com/projects/689.svg
[tip-url]: http://tip4commit.com/projects/689