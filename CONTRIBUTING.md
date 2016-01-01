# Contributing

## Report an Issue

* https://github.com/kanreisa/Chinachu/issues

When reporting an issue we also need as much information about your environment
that you can include. We never know what information will be pertinent when
trying narrow down the issue. Please include least the following information:

* Version of Chinachu: `sudo npm list -g chinachu`
* Version of Mirakurun: `sudo npm list -g mirakurun`
* Platform you're running on (Debian jessie, CentOS 7.1, ...)
* Architecture you're running on (x86 or x64)

**Please note: ARM architectures currently not supported.**

## Development

To get started, [sign the Contributor License Agreement](https://www.clahub.com/agreements/kanreisa/Chinachu).

### Pull Request

Please PR to the [devel-air](https://github.com/kanreisa/Chinachu/tree/devel-air) branch.
Please don't PR to the master branch it's protected.

### Checkout

```
git clone git@github.com:kanreisa/Chinachu.git
cd Chinachu
git checkout devel-air
git submodule init
git submodule update
```

### Build

```
npm install
npm run tsd-install
npm run build
```

### Install

```
sudo npm install . -g --unsafe
```

If you've any questions, please ask on Slack.