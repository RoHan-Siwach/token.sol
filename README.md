 # MyToken
- This Solidity smart contract represents a basic token contract named "MyToken." It includes functionality for minting (creating) and burning (destroying) tokens, as well as public variables to store information about the token.

![Screenshot](Screenshot(435).png)


 # Description
- The contract includes the following features:

 # Public variables:

- tokenname: A string representing the name of the token ("META" in this case).
- tokenabbrv: A string representing the token's abbreviation ("MTA" in this case).
-totalsupply: A uint representing the total supply of the token, initialized to 0.
- Mapping variable:

- balances: A mapping that associates addresses with token balances.
- Mint function:

- mint(address _address, uint _value): Increases the total supply and the balance of a specific address by a specified value.
- Burn function:

- burn(address _address, uint _value): Decreases the total supply and the balance of a specific address by a specified value, but only if the address has sufficient balance.
  
# Getting Started
- Executing program
- To deploy and interact with this contract, you can use Remix, an online Solidity IDE. Follow these steps:

- Go to the Remix website at https://remix.ethereum.org/.
- Create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., MyToken.sol).
- Copy and paste the provided code into the file.
- Compile the code by clicking on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.24" (or another compatible version), and then click on the "Compile MyToken.sol" button.
- Deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "MyToken" contract from the dropdown menu, and then click on the "Deploy" button.

# Authors
- Rohan Siwach
