# Contracts with Solidity

## Background
This project builds a smart contract to automate company finances to increase transparency and automate accounting and auditing.

These contracts will do several things:
- Pay your Associate-level employees quickly and easily
- Distribute profits to different tiers of employees
- Distribute company shares for employees in a "deferred equity incentive plan" automatically

## Level One: The AssociateProfitSplitter Contract
This contract accepts Ether into the contract and divides the Ether evenly among the associate level employees which allows the Human Resources department to pay employees quickly and efficiently.

## Level Two: The TieredProfitSplitter Contract
This contract distributes different percentages of incoming Ether to employees at different tiers/levels. For example, the CEO gets paid 60%, CTO 25%, and Bob gets 15%.

## Level Three: The DeferredEquityPlan Contract
Level Three is a DeferredEquityPlan that models traditional company stock plans. This contract will automatically manage 1000 shares with an annual distribution of 250 over 4 years for a single employee. This part of the contract, manages an employee's "deferred equity incentive plan" in which 1000 shares will be distributed over 4 years to the employee. It stores and sets amounts, that represent the number of distributed shares, the employee owns and enforces the vetting periods automatically.

The video that demonstrates all three contracts.
