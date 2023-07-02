# nodejs
starter project for nodejs
sudo apt update
sudo apt upgrade

####
https://learn.microsoft.com/en-us/windows/dev-environment/javascript/nodejs-on-wsl
###

//get curl
sudo apt-get install curl

//get nvm
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/master/install.sh | bash

//verify nvm
command -v nvm
nvm ls

//install LTS Stable nodejs
nvm install --lts

//install current node
 nvm install node

// 
nvm use <node, LTS,  v8.2.1>

//list remote avail:
nvm ls-remote

