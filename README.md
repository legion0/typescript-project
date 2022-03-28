# Project Documentation

## Setup

```shell
sudo apt update
sudo apt install python2 build-essential

# Install NVM: https://github.com/nvm-sh/nvm#installing-and-updating

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash

# Screeps driver requires node version <= 12

nvm install v12.22.10 && nvm use v12.22.10

rm -rf node_modules && npm install
```

## Testing

`npx jest` or `npx jest --watch`
