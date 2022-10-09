# web3-html

To run: 


1. First do this to start local node: 

cd hardhat-simple-storage
yarn 
yarn hardhat node

2. Now install Metamask in your chrome browser from chrome extensions: https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=en

3. Import account with private key to metamask instance, private key: 0xac0974bec39a17e36ba4a6b4d238ff944bacb478cbed5efcae784d7bf4f2ff80

4. In Metamask, click Networks > Add Network:
    Network name: hardhat-localhost
    RPC URL: http://127.0.0.1:8545/
    chainId: 31337
    currency symbol: ETH

5. Select the network hardhat-localhost

6. open a new terminal

7. run yarn browserify index.js --standalone bundle -o ./dist/bundle.js

8. run index.html











