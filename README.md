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

