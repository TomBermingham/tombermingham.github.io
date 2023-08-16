# tombermingham.github.io

Go to https://tombermingham.github.io/ to view

Refresh the page if you get an error.

It loads the HTML content from the smart contract. The address of the smart contract is in the query string in the URL.
e.g. https://tombermingham.github.io/?address=0xee7A60172c138615F4C6ECf6E2A6b24720B4bce0

The smart contract at that address has a function called retrieve() which returns a string. The string is the HTML for the page.

You can make your own website on the blockchain by deploying a contract with a function called retrieve() which returns a string.

Just put the contract address in the query string: https://tombermingham.github.io/?address=CONTRACT_ADDRESS
