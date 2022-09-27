Hello, and thank you for your purchase! This README.txt file will pose as a set of instructions for the attached gcoach.sol file. This is the contract code that you will use to create and deploy your token. Please note, that deviating from any of these steps may result in bugs/problems with your token




***INSTRUCTIONS***

1. Head over to Ethereum Remix (https://remix.ethereum.org) and open up a blank workspace- which should be the default page.

2. Above the “contracts” folder in the left column should be four icons: create new file, create new folder, publish all workspace files to github, and load a local file into current workspace respectively.  Of these options, you want to click on the “load a local file into current workspace” option. From here, you want to upload the provided gcoach.sol file.

3. If you click on the “contracts' folder in Ethereum Remix, you should see the gcoach.sol file. Click on this file to open it up in the editor (NOTE: this is the ONLY file you will need to edit!)

4. On line 157, you will see a token wallet address. Replace this wallet address (and ONLY the wallet address) with the wallet address of the token owner (in most cases, this will simply be your token wallet address). Double click on the current address displayed, and paste in your chosen token owner address. If you need help finding your token address, you should be able to do this within MetaMask.

5. On line 365 should be displayed “Contract Comfy Rocket is Context, IERC20, Ownable”. Here, you want to replace “Comfy Rocket” with the name of your token.

6. On line 374, should be displayed “developmentWalletAddress = (Address)”. This wallet is set up to be a charity wallet, which can be used for whatever you desire (ex- charity wallet, marketing wallet, burn wallet, etc.). This token address should be different from the one associated with the token owner's address (to create a new wallet in MetaMask, click My Accounts > Create account). Copy your chosen address, and double click on the current address and paste the new address to replace it with.

7. In line 376, you can edit the amount of tokens (which currently, is set to 1 trillion). Feel free to edit this number to whatever you desire.

8. On line 379, You will input the name of your token. Feel free to replace the current name provided (Comfy Rocket) with the chosen name of your token. (NOTE: this MUST match the name of the token on line 365)

9. On line 380, you will replace the current token symbol “COMF” with your tokens respective 4-letter symbol.

10. On line 382, is an option for a token tax fee (also known as reflections). This is a fee deducted and redistributed to your token holders each and every time a transaction happens. This is currently set to 5%, Which should be displayed as “50” (NOTE: With fees, there will always be an extra zero). To set the fee, replace this number with the percentage fee that you desire, and end it with a zero. If there is no token tax fee, set this number to “0”

11. On line 384, is an option for a to set the development fee. This is the percentage put into the charity wallet that you chose in step 6. This is currently set to 2%, Which should be displayed as “20” (NOTE: With fees, there will always be an extra zero). To set the fee, replace this number with the percentage fee that you desire, and end it with a zero. If there is no token tax fee, set this number to “0”.

12. On line 386, is an option for a to set the liquidity fee. This is the percentage put into your tokens liquidity pool. This is currently set to 3%, Which should be displayed as “30” (NOTE: With fees, there will always be an extra zero). To set the fee, replace this number with the percentage fee that you desire, and end it with a zero. If there is no token tax fee, set this number to “0”.

13. In this example, the total token tax when added up should be 12%. This means that each transaction has a tax of about 12% that is distributed however you see fit. Please note that the token fee should be lower than about 10% for a cleaner audit.

14. Well done! You have now completed your token! To publish your token contract address, you want to click on the solidity logo right below the file explorer within the left column (which should be labeled with either a green checkmark or a loading wheel). You will be prompted to pick a compiler version, which in this case you will want to *pick version 0.8.4*.

15. On this same page, click on both the checkboxes for “auto compile” and “enable optimization”. 

16. Click on the blue *Compile* button

17. Once that is done, click on the “deploy and run transactions” button within the left column- which should be the ethereum logo right below the solidity logo.

18. For the environment, please select “Injected Web3”

19. Change the contract to “(YourTokenName) - contracts/gcoach.sol”

20. Press the orange “Deploy” button. Please note that you need to pay a small BNB fee before you can deploy.

21. Once transaction is confirmed, please click on the provided transaction link to see the status of your contract creation, as well as your tokens information.

22. On the BscScan page, once your contract is published, copy the link on the line titled “Interacted With (To)”- as this is your tokens contract address.

23. Congratulations! You're done programming your code! This final product should be fully functional to your preferences, and the contract will be verifiable on BscScan without any issues. Once you do this, you should be able to upload a logo for your token and manage it on BscScan without issue!I hope you are satisfied! Cheers! :)
