Here’s an updated version of your README for the **DeFi Lending-and-Borrowing DApp** project:

---

# DeFi-Lending-and-Borrowing DApp

A decentralized lending platform that allows users to lend and borrow crypto assets, earning passive income through interest on their deposits. It’s a fully on-chain DeFi application, rewarding users with a custom ERC20 token (LAR) for supplying tokens and enabling collateralized borrowing.

Deployed on the Ethereum Kovan Network.

## Features
1. Supports 4 test tokens: DAI, LINK, WETH, and FAU.
2. Users can provide liquidity or use their tokens as collateral for borrowing.
3. Lenders are rewarded with LAR tokens, calculated based on the dollar value of their supplied tokens.
4. Borrowers must provide collateral greater in value than the amount they borrow, influenced by the LTV ratio of the token.
5. Stable APY rate for borrowed tokens ensures constant interest rates.
6. Borrowers repay both the borrowed amount and interest. After repayment, collateral can be withdrawn.
7. LAR tokens rewarded are collected when a user withdraws their supplied tokens, equivalent to the value of the withdrawn amount.

## Technologies
- **OpenZeppelin**: For IERC20 and security via Ownable contracts.
- **Chainlink**: Fetches real-time price feeds using AggregatorV3Interface.
- **Truffle**: Development environment for smart contracts.
- **Ganache**: Local blockchain for testing.
- **Next.js**: Frontend framework for seamless user interaction.
- **Tailwind CSS**
- **Metamask**
- **Web3.js**

## Programming Languages
- Solidity
- Truffle
- JavaScript
- Next.js

## Installation and Setup
1. **Tailwind CSS**: [Install Tailwind CSS](https://tailwindcss.com/docs/installation)
2. **Deploy on Kovan**:
   ```bash
   truffle deploy --network kovan
   ```
3. **Start the server**:
   ```bash
   npm run dev
   ```

## Developer
Let’s Connect! 👋 👋  
- **Harpreet Singh**  
  Email: happybiostockcode07040@gmail.com  
  [LinkedIn](https://www.linkedin.com/in/harpreet-singh-031528284/)  
  [Portfolio](https://www.linkedin.com/in/harpreet-singh-031528284/)

---

Let me know if you’d like any changes or additions!
