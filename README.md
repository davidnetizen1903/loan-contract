# Collateralized Loan Contract

To write the core logic of the contract. It may be helpful to read [Writing a Contract That Handles Ether](https://programtheblockchain.com/posts/2017/12/15/writing-a-contract-that-handles-ether/) if you haven’t already:

Borrowing ether using ERC20 tokens as collateral is an example transaction that a smart contract can broker easily. To keep payments really simple, I will assume that loans are paid off with a single ether payment that must be made before a given deadline. Here is [detailed explanation](https://programtheblockchain.com/posts/2018/03/06/writing-a-collateralized-loan-contract/)