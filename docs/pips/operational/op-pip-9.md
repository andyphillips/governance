# Operational PIP 9: Add Asymmetric Research as a Pythnet validator

## Abstract

Delegate a Pythnet Stake Account to Asymmetric Research to enable them to run a validator for Pythnet.

## Rationale

Validator diversity is very important for the reliability of the network.
Asymmetric Research is a new validator provider that has expressed interest in joining Pythnet.

## Description

Pythnet is Pyth's appchain. The stake on Pythnet is fully controlled by the Pythian Council, who controls all of the Stake accounts and chooses who to delegate them to.

Asymmetric Research is a boutique security venture focused on deep partnerships with L1/L2 blockchains and DeFi protocols in an effort to keep them safe. Their website : https://www.asymmetric.re/


## Implementation Plan

* Proposal id: [`DCCzA6f25fR7VGXfW9LL6WjyAYQMg42B8EiZmueRvDF2`](https://proposals.pyth.network/?tab=proposals&proposal=DCCzA6f25fR7VGXfW9LL6WjyAYQMg42B8EiZmueRvDF2)


* Verify the implementation following the guide below:

1. Check that <stake account> is an undelegated stake account. You can do this by running `solana -u https://pythnet.rpcpool.com stakes` in your terminal, and looking for <stake account>.
2. Check that the <vote account> is the key provided by Asymmetric Research as a part of this proposal: `AR1vDzBzaq1nD19naVMfgTKeM5ifHd7rbxdvyMuG6njg`
