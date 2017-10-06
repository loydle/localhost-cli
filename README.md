localhost-cli 
===========================

Start a node.js server from the command line :)

### Usage
`$ localhost` 

// Server listening on port 3000  
----------
### Install 
Git clone

`$ mv [download_directory]/personal_bin/localhost ~/.personal_bin/localhost`

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

