# Equity-Plan-Smart-Contract

Ethereum-compatible blockchain to help connect financial institutions, and the team wants to build smart contracts to automate some company finances to make everyone's lives easier, increase transparency, and to make accounting and auditing practically automatic! These smart contracts are capable of delivering following functionalities.

- Pay your Associate-level employees quickly and easily.

- Distribute profits to different tiers of employees.

- Distribute company shares for employees in a "deferred equity incentive plan" automatically.

# Equity Plans

There are three Smart Contracts for each following Equity Plans.

- Level One (AssociateProfitSplitter Smart Contract)

- Level Two (TieredProfitSplitter Smart Contract)

- Level Three (DeferredEquityPlan Smart Contract)

# Associate Profit Splitter

This will accept Ether into the contract and divide the Ether evenly among the associate level employees. This will allow the Human Resources department to pay employees quickly and efficiently.

## Deposits

<p align="center">
  <img src="https://github.com/chirathlv/Equity-Plan-Smart-Contract/blob/main/Images/AssociateProfitSplitter%20Accounts%20Deposits.PNG">
  <img src="https://github.com/chirathlv/Equity-Plan-Smart-Contract/blob/main/Images/AssociateProfitSplitter%20Accounts%20Deposits%20Confirmation.PNG">
  <img src="https://github.com/chirathlv/Equity-Plan-Smart-Contract/blob/main/Images/AssociateProfitSplitter%20Accounts%20Deposits%20Verification.PNG">
</p>

## Checking Before and After Balance

<p align="center"><b>Account Balances (Before)</b></p>
<p align="center">
  <img src="https://github.com/chirathlv/Equity-Plan-Smart-Contract/blob/main/Images/AssociateProfitSplitter%20Before%20Accounts%20Balances.PNG">
</p>
<p align="center"><b>Account Balances (After)</b></p>
<p align="center">
  <img src="https://github.com/chirathlv/Equity-Plan-Smart-Contract/blob/main/Images/AssociateProfitSplitter%20After%20Accounts%20Balances.PNG">
</p>

# Tiered Profit Splitter

This will distribute different percentages of incoming Ether to employees at different tiers/levels. For example, the CEO gets paid 60%, CTO 25%, and Bob gets 15%.

## Deposits

<p align="center">
  <img src="https://github.com/chirathlv/Equity-Plan-Smart-Contract/blob/main/Images/TieredProfitSplitter%20Accounts%20Deposits.PNG">
  <img src="https://github.com/chirathlv/Equity-Plan-Smart-Contract/blob/main/Images/TieredProfitSplitter%20Accounts%20Deposits%20Confirmation.PNG">
  <img src="https://github.com/chirathlv/Equity-Plan-Smart-Contract/blob/main/Images/TieredProfitSplitter%20Accounts%20Deposits%20Verification.PNG">
</p>

## Checking Before and After Balance

<p align="center"><b>Account Balances (Before)</b></p>
<p align="center">
  <img src="https://github.com/chirathlv/Equity-Plan-Smart-Contract/blob/main/Images/TieredProfitSplitter%20Before%20Accounts%20Balances.PNG">
</p>
<p align="center"><b>Account Balances (After)</b></p>
<p align="center">
  <img src="https://github.com/chirathlv/Equity-Plan-Smart-Contract/blob/main/Images/TieredProfitSplitter%20After%20Accounts%20Balances.PNG">
</p>

# Deferred Profit Splitter

This will model traditional company stock plans. This contract will automatically manage 1000 shares with an annual distribution of 250 over 4 years for a single employee.

## Deployment

This contract is deployed into Kovan Testnet which can be tracked using below URL.

https://kovan.etherscan.io/tx/0x486b2bf1c1d6abffe2d7345a6c8bb84494782fa80ce6f67404ec4b2d01c5f4d7

<p align="center">
  <img src="https://github.com/chirathlv/Equity-Plan-Smart-Contract/blob/main/Images/DeferredEquityPlan%20MetaMask%20Etherscan%20Details.PNG">
</p>

## Account Interaction using fastforward function

<p align="center">
  <img src="https://github.com/chirathlv/Equity-Plan-Smart-Contract/blob/main/Animation.gif">
</p>
