# localhost-cli 
> Start an easy to custom node.js server from the command line. :seedling: :thumbsup:

## Usage
`$ localhost` 

![usage](https://img11.hostingpics.net/pics/997803Capturedcran20171006221435.png)

----------
## Install 

`$ git clone https://github.com/loydle/localhost-cli.git`

`$ cp -r [download_directory]/localhost-cli /usr/local/bin/localhost`

`$ cd /usr/local/bin/localhost`

`$ npm install`

`$ chmod 755 /usr/local/bin/localhost/localhost`

`$ vim ~/.bash profile`


add the following line to ~/.bash_profile 

```bash
export PATH=$PATH:.

```
### Restart terminal, done! :thumbsup:

----------

## Even better?
###  Use config-manager-cli to edit the server in one command :boom:
see: https://github.com/loydle/config-manager-cli

### Add config files
`$ ln /usr/local/bin/localhost/localhost ~/.personal_config/localhost`

#### Usage
`$ config localhost`


-----------------

### MIT License

2017 DigitalSC.org

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
