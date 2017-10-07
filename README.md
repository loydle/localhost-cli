localhost-cli 
===========================

Start an easy to custom node.js server from the command line.

### Usage
`$ localhost` 

![usage](https://img11.hostingpics.net/pics/997803Capturedcran20171006221435.png)

----------
### Install 

`$ git clone https://github.com/loydle/localhost-cli.git`

`$ mv [download_directory]/localhost-cli ~/.personal_bin/localhost`

`$ cd ~/.personal_bin/localhost`

`$ npm install`

`$ chmod 755 localhost`

`$ vim ~/.bash profile`


add the following line to ~/.bash_profile 

```bash
export PATH=$PATH:.:$HOME/.personal_bin/localhost:

```
----------

###  Use config-manager-cli to edit the server in one command
https://github.com/loydle/config-manager-cli

#### Add config files
`$ ln ~/.personal_bin/localhost/localhost ~/.personal_config/localhost`

#### Usage
`$ config localhost`


-----------------

### MIT License

Copyright (c) 2016 Stephan Schultz

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
