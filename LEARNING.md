LEARNING.md

Reflections on Building My First ERC-20 Token

📌 Overview

This project was my first hands-on experience with blockchain development and the Ethereum ecosystem. By creating an ERC-20 token from scratch, I understood not just how cryptocurrencies work on the surface, but how they function internally at the smart-contract level. This project helped me connect programming concepts with real blockchain behavior.

🎯 What I Learned
1. Understanding ERC-20 Standard

Before this project, “ERC-20” was just a commonly heard crypto term.
Now I understand:

It is a set of rules (standard interface)

Wallets, exchanges, and apps rely on these common functions

Functions like transfer, approve, transferFrom, balanceOf, and allowance are mandatory

This helped me appreciate why token standards exist and how they ensure interoperability.

2. Solidity Basics

I became comfortable with:

Declaring state variables

Using mappings for balance and allowance tracking

Writing constructors

Using require() for validation

Emitting events for transparency

I also learned Solidity naming conventions and the importance of gas-efficient code.

3. Token Economics (Tokenomics) Fundamentals

By setting:

name

symbol

decimals

totalSupply

I clearly understood how tokens represent value and how 18 decimals make the token behave like ETH.

4. How Transfers Actually Work

Implementing transfer() made me understand:

How balances are updated

Why zero-address checks matter

How events help wallets detect token movements instantly

I also realized the importance of ordering state changes before emitting events.

5. Allowance & Spending Mechanism

The approve → transferFrom flow gave me a deeper understanding of:

How DApps and smart contracts spend tokens on behalf of users

Security concerns with unlimited allowances

Why allowances must decrease to avoid misuse

This is one of the most critical concepts in token contract design.

6. Working with Remix IDE

I learned how to:

Create, compile, and deploy contracts

Use JavaScript VM for safe testing

Inspect transactions and event logs

Switch accounts and simulate real blockchain interactions

This gave me confidence in interacting with deployed smart contracts.

7. Debugging & Common Mistakes

Through trial and error, I learned:

Why transfers to address(0) should be blocked

Why balance checks prevent token loss

Importance of decreasing allowance in transferFrom

Using uint256 for all token values to avoid overflow

These mistakes taught me the practical safety issues in smart contracts.

🚀 Personal Growth & Reflections

This project made blockchain feel less abstract and more programmable.

I realized how simple logic can power huge systems like DeFi and crypto exchanges.

Writing secure code became more important than just writing code that “works”.

I gained confidence in reading and reasoning through smart contract standards.

It encouraged me to explore deeper topics like minting, burning, pausing, and ownership patterns.

Most importantly, this project gave me the belief that I can now build real blockchain applications, not just learn theory.

📚 Next Steps in My Learning Journey

I plan to extend my ERC-20 contract with:

Mint & Burn functionality

Ownable access control

Pausable mechanism

Gas optimization

Deployment to a public Ethereum testnet

Integration with MetaMask

This project has opened the door to more advanced smart contract development.

✅ Final Reflection

Building my first ERC-20 token was a foundational step in my blockchain journey. It gave me a strong practical understanding of Ethereum smart contracts, token standards, and Solidity programming. The experience was both educational and motivating, and it has inspired me to continue exploring blockchain development.
