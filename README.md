# project_blockbase
It's my first project in web3 doamin. BlockBase 2025, organized by FEC, IITG by This 7-day certified crash course I  🔹 Understood the core principles of blockchain technology🔹 Learnt Solidity to write and deploy smart contracts 💻 🔹 Built &amp; launched my first decentralized app (dApp) ✨
[View Certificate of Completion](project_blockbase/blockbase_cirtificate.pdf)


**Prerequisites**
1. Node.js and npm installed (if not installed, check this out)
2. MetaMask browser extension installed
3. Some Sepolia testnet ETH (you can get this from a Sepolia faucet)

**to make it**:
-Run the following commands in terminal:
-npx create-react-app expense-tracker-dapp
-cd expense-tracker-dapp
-npm install ethers@5.7.2 @openzeppelin/contracts (this is a dependency to
be installed)
- Set up the ABI file (we have provided it for your convenience)
    1. Create a file in the src folder called ExpenseTrackerABI.json
    2. Copy and paste the ABI from Remix:
    ○ In Remix, go to the "Solidity Compiler" tab
    ○ Click on the "Compilation Details" button
    ○ Find and copy the ABI section (ABI is besides bytecode)
    ○ Paste this into your ExpenseTrackerABI.json file
- Set up the files
    1. Replace the content of src/App.js with the provided App.js code
    2. Replace the content of src/App.css with the provided App.css code
-Update the contract address
    In App.js, locate this line:
    const contractAddress = "YOUR_CONTRACT_ADDRESS_HERE";
    Replace YOUR_CONTRACT_ADDRESS_HERE with the actual contract address you
    got when deploying via Remix.
**How to Use the dApp**
1. Connect your MetaMask wallet (make sure it's set to Sepolia testnet)
2. Register with your name
3. Add expenses with participants, their contributions, and what they owe
4. View expense history
5. See the net debt or profit you are in
6. You have to register the other person (Parth, here) from their own wallet
and they can see the expense history of the transactions they are
involved in, as well ! (Make sure both are using the same smart contract
address)
Initially when you just enter you can see the expenses along with the people.
After you click on refresh expenses, the history loads. The net balance can be
seen in the People Table.
    
