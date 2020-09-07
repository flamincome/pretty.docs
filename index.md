# flamincome

> the most efficient farmer on [*flamingo*](https://flamingo.finance)

## notice

**USE AT YOUR OWN RISK!!!**

# Introduction

[*flamincome*](https://flamincome.github.io) farms on [*flamingo*](https://flamingo.finance) and earn profits.

```
users -------+                        +-> flamingo dao
             |                        |-> flamingo vault
strategists ---> vaults ---> actions ---> flamingo swap
             |                        |-> flamingo perp
governances -+                        +-> other productions
```

Users deposit (or withdraw) tokens to (or from) [*flamincome*](https://flamincome.github.io) vaults, where they are allocated to different DeFi protocols/pools with the goal of maximizing their APY.

This optimized allocation of tokens will be done through an strategist, a party that's heavily restricted in what it can do, as it can only take actions from a whitelisted set that is directly encoded in the contract, which will initially be a chosen operator that will be transitioned into a smart contract.

The strategist will then use the tokens present in the vaults to farm the several [*flamingo*](https://flamingo.finance) protocols (as well as others) in an optimal way.

See [Strategies](/strategies) for a list of all whitelisted actions available to the strategist.

This whole protocol will then be managed in a decentralzied way through a DAO, which will have access to all vaults, and will be able to change the strategist or the actions it is capable of performing.

# Strategies

The actions that will be available to the strategist initially will be:

- staking
- liquidity
- liquidation
- arbitrage
- governance
- adjustment
- derivatives

This set of actions can also be altered through a decentralized governance process.

# Governance

NEP-5 token `FLAM` will be the governance token of [*flamincome*](https://flamincome.github.io).

`FLAM` will be gradually released to [*flamincome*](https://flamincome.github.io) following the pace of the [*flamingo*](https://flamingo.finance) token.

*TODO: GOVERNANCE DETAILS*

# Culture

As a fully community-based project, [*flamingo*](https://flamingo.finance) will always be open.

With no pre-mine, founder shares or VC-allocated tokens, everything will be distributed to the community, which will hold all the power over what to do with the protocol.

Just remember that it is your own duty to ensure the safety of your tokens and profits, so use at your own risk.

Join the governance and make it better.

<footer>
<a href="https://flamincome.github.io">home</a>
<a href="https://flamincome.github.io/docs">docs</a>
<a href="https://flamincome.github.io/logo">logo</a>
</footer>
