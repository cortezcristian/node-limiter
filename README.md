# node-limiter
Node CPU limiter

This utility may help you reduce all the fan noise coming out from the machine, when running node projects.

## Usage

```bash
$ node-limiter -t 10 -c 77 -l chrome,mongo
```

This command will check for new processes every 10 seconds, and the max cpu percentage limit is set to 77. For all the process that matches chrome or mongo.


## Installation

```bash
$ npm install -g node-limiter
```

You'll need to install [cpulimit](https://github.com/opsengine/cpulimit).

```bash
$ [sudo] apt-get install cpulimit # Ubuntu
$ brew install cpulimit # OSX
```

## Credits
[@cortezcristian](https://twitter.com/cortezcristian)
See [LICENSE](https://github.com/cortezcristian/node-limiter/blob/master/LICENSE)
