# ETH-proof-beginner-project

# Tokens
REQUIREMENTS THAT NEEDS TO BE MET: 
1. Your contract will have public variables that store the details about your coin (Token Name, Token Abbrv., Total Supply)
2. Your contract will have a mapping of addresses to balances (address => uint)
3. You will have a mint function that takes two parameters: an address and a value. 
       The function then increases the total supply by that number and increases the balance 
       of the “sender” address by that amount
4. Your contract will have a burn function, which works the opposite of the mint function, as it will destroy tokens. 
       It will take an address and value just like the mint functions. It will then deduct the value from the total supply 
       and from the balance of the “sender”.
5. Lastly, your burn function should have conditionals to make sure the balance of "sender" is greater than or equal 
       to the amount that is supposed to be burned.

> A TOKEN CONTRACT IS CREATED THAT HAS THE token Name, token Abbrevation, and thhe total supply that is present.
> Here, the mint and burn function are created to create and delete the tokens from a specific address i.e. the user.

# Executing the Program
> To run this program, you can use Remix, an online Solidity IDE. which is available online.
> Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension
> Copy and paste the code from the above file.
> To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.7", and then click on the "Compile" btn.
> Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar.
> Setting the Gas limit either it is custom or estimated.
> Then clicking on "Deploy" button.

Once the contract is deployed, you can interact with it by calling the functions.
