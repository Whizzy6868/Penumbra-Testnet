# Penumbra-Testnet
## The Set Up

``sudo apt update``

``sudo apt upgrade -y``

## Install curl

``sudo apt install curl``

### INSTALL SCRIPT WITH CURL
##### this is the latest version but always check https://guide.penumbra.zone/main/pcli/install.html for latest version 

``curl -O -L https://github.com/penumbra-zone/penumbra/releases/download/v0.66.0/pcli-x86_64-unknown-linux-gnu.tar.xz
unxz pcli-x86_64-unknown-linux-gnu.tar.xz
tar -xf pcli-x86_64-unknown-linux-gnu.tar
sudo mv pcli-x86_64-unknown-linux-gnu/pcli /usr/local/bin/``
``# confirm the pcli binary is installed by running:
pcli --version``

### RUN COMMAND TO CONFIRM INSTALLATION

``pcli --version``

### Run this if you are creating a new wallet

``pcli init soft-kms generate``

### Run this if you want to import wallet 

``pcli init soft-kms import-phrase``

then input seed phrase,
the output will be like below

``Writing generated configs to [PATH TO PCLI DATA]``

### Run this to sync

``pcli view sync``

### Run this to view address 

``pcli view address 0``

### Go to discord and claim faucet in the #testnet-faucet channel https://discord.gg/u25wjzqp
claim for days once every 24hrs. 

### Check balance

``pcli view balance``

### Run the code below to contribute

``pcli ceremony contribute --phase 1 --bid 60penumbra --coordinator-address penumbra1qvqr8cvqyf4pwrl6svw9kj8eypf3fuunrcs83m30zxh57y2ytk94gygmtq5k82cjdq9y3mlaa3fwctwpdjr6fxnwuzrsy4ezm0u2tqpzw0sed82shzcr42sju55en26mavjnw4``

## Note the mininum contribution is 60penumbra and you are free to edit to the amount you desire, Phase1 contribution currently closed wait for phase 2. Keep claiming faucet and play around the webchrome wallet.
