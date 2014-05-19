# set-env [![NPM Version](https://badge.fury.io/js/set-env.svg)](https://badge.fury.io/js/set-env)

WORK IN PROGRESS

Sets additional launch environment variables.

### Install

```sh
$ npm install -g set-env
```

## Usage

Only works with OS X at the current time. OS X 10.9.0+ tested.

Sets to `/etc/launchd.conf/` on OS X.

```sh
$ set-env <env-variable> <value>
```

### Example

```sh
$ set-env GITHUB_USERNAME Fishrock123
> Writing out:
setenv GITHUB_USERNAME Fishrock123

```

## License

The MIT License (MIT)

Copyright (c) 2014 Jeremiah "Fishrock123" Senkpiel fishrock123@rocketmail.com

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
