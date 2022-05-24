
Transparent Voting System

**************************


Creating and Connecting MetaMask wallet:

1) Add the MetaMask extension to your chrome browser.
2) Click on MetaMask and create a new wallet.
3) Enable "Show test networks" in the settings.
4) Choose "Rinkeby test network" in the dropdown menu in the top right corner.
5) Open "https://faucets.chain.link/" in the new tab and click on "Connect Wallet" and choose "MetaMask".
6) Uncheck the "10 test Link" and click on "send request".
7) Follow the above steps to create multiple wallets for voters.


Compiling the solidity file: 

1) Open "Voting. sol" which is inside the  "Contracts" folder in any code editor(Ex. VS Code) and copy the entire content.
2) Go to "http://remix.ethereum.org/" and create a new file as "Voting.sol" and paste the content into the created file.
3) Click on "Compile Voting.sol" under the third menu in the left sidebar.
4) Inside the "Deploy & run transaction" menu in the left sidebar change the environment to "Injected Web3" and in the MetaMask popup choose any one account to use as an admin account and click on "Deploy".
5) Once deployed copy the address code which is on the left bottom and the "transaction hash" code under the deploy drop down in the console6) Open the "Voting.json" under "Client > src > contracts" and at the bottom of the file where you can "address" and "transactionhash" under the "networks" object and paste the value respectively.


Running the application:

1) Open "Command Prompt" and change the directory to the "Client" folder.(Ref:"https://www.geeksforgeeks.org/cd-cmd-command/").
2) Run the following two commands one after another
      => npm install
      => npm start
3) Application will start in a new browser tab.