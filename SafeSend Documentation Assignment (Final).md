# SafeSend Documentation Assignment

## TL;DR
- Protect your wallets and assets from malicious actors!
- Ensure your transactions are going exactly where you intend.
- Ensure your experience in DeFi and and crypto is a safe one!

## Overview
SafeSend is a new product from the team at NodeOps, as another tool to keep users safe while using DeFi applications and interacting with new projects.


## Pre-requisites
- Wallet Software - Phantom, Metamask, SubWallet, Argent, Rabby, Coinbase Wallet, or similar.
- Adequate gas token holdings for network fees (*ex. ETH on Ethereum, Arbirtum, or Base, and BNB for Binance Smart Chain*) and tokens for the desired transfer.

<details>
<Summary> Wallet must be able to connect to one of the following supported networks:</Summary>

- #### Arbitrum One <br>
- #### Arbitrum Sepolia<br>
- #### Base
- #### Binance Smart Chain (BSC) <br>
- #### Ethereum <br>
</details>


## Benefits of SafeSend
SafeSend was designed to mitigate the potential of user error and malicious actors in DeFi. Say goodbye to typos sending your assets to the wrong address or contract, fat fingers setting your gas fees to 1001 instead of 0.1001, exposure to dangers of infinite allowances, and more.

## Target Groups
SafeSend can be useful to a variety of users:

- Users new to DeFi and Crypto may use the tool for additional guardrails as they get comfortable with blockchain interactions.
- DeFi Power users may use the tool to provide more security and checks before aping into that brand new protocol that was deployed an hour ago with juicy APY's.
- Developers may use this tool during testing of new contract deployments to ensure they don't lose funds while testing new functionalities, or could integrate SafeSend into their dApps to provide an additional layer of protection for their users.

## How to Use / How it Works
Users can use SafeSend by following 5 easy steps:

**1. Connect your Wallet** <br>
	- Use WalletConnect to connect your wallet. <br>
    - Verify wallet ownership by signing a message. Click "Verify Wallet" and your wallet should receive a signature request.

<details>
<Summary> Safety Note</Summary>

- *The request should come from safesend.to and should include the message: "Please verify your wallet to confirm ownership. You are responsible for submitting the correct address."*
</details>
<br>

**2. Select Token and enter recipient address details.** <br>
	- Supported tokens include NODE, WETH, USDT, and USDC. <br>
    - Please ensure recipient address is entered correctly!

**3. Approve Token Transfer** <br>
	- A new window will load with the entered transaction details. Click "Approve" to prompt an approval request in your wallet. SafeSend requests approval for the exact token amount - no infinite approvals here! Exact approvals prevent unauthorized transfers and risks of later lost funds due to infinite approvals. <br>
	-Once the approval is confirmed, SafeSend will show a "Start Test Tx" button. This will push the amount you specified in your test transaction field to the recipient address.

**4. Telegram Confirmation** (***Is this implemented yet?***) <br>
	- The recipient receives a secure Telegram notification to confirm transaction details before execution. This adds security and prevents accidental transfers to wrong addresses.

**5. Secure Execution** <br>
	- SafeSend automatically executes the transfer on-chain, waits for confirmation, and provides transaction hash with blockchain explorer links for the chosen network. You will be provided transaction hashes for both the test transaction and full follow-up transaction for reference. You may also return to the "History" tab in the app to review your sent transactions and retrieve transaction hashes.

## SafeSend Features

- Secure Token Transfer
- Multi-Chain Support
- Test Transaction Verification
- Telegram Bot Integration
- Wallet Connection
- Transaction History
- Approval-Based Transfers
- Ability to add custom token transfers on supported networks.


## Limitations
Currently SafeSend is only available on the supported networks listed above. Stay tuned for additional network support as it becomes available.
SafeSend currently supports a limited token set of NODE, WETH, USDT, and USDC depending on the network used. More tokens may be added in the future, so stay tuned.

<details>
<Summary> Supported Tokens</Summary>

#### Arbitrum One
NODE, USDC, USDT
#### Ethereum
NODE, USDC, USDT
#### Binance Smart Chain
NODE, WETH, USDC, USDT
#### Arbitrum Sepolia
NODE_TEST
#### BASE
USDC, USDT
</details>
<br>
Alternatively, advanced users may use the "Add Custom Token" feature to add additional tokens on supported networks, given the user has the token contract address and basic details available to input.
<br><br>

**Please confirm all details are correct before continuing with a custom token transfer! This feature is available to users at their own risk.**

Want to see a new supported token? Drop us a note in our [Discord server] or tag us with a request on [X]!

[//]

[Discord server]: <https://discord.com/invite/JCZgbSZqaH>

[X]: <https://x.com/NodeOpsHQ>






