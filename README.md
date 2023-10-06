# MyToken Solidity Smart Contract

**Table of Contents:**

1. [Introduction](#introduction)
2. [Contract Overview](#contract-overview)
3. [Public Variables](#public-variables)
4. [Mapping Variable](#mapping-variable)
5. [Mint Function](#mint-function)
6. [Burn Function](#burn-function)

## Introduction

This repository contains a Solidity smart contract named "MyToken" that implements a basic ERC20-like token functionality. The contract includes features such as minting and burning tokens, as well as maintaining token balances for addresses.

## Contract Overview

The "MyToken" contract is a simple example of a token contract in Solidity. It provides basic functionalities to mint and burn tokens, along with tracking balances for different addresses. The contract is based on the ERC20 token standard but is a minimal implementation for educational purposes.

## Public Variables

- `tokenName`: A public string variable that represents the name of the token (e.g., "META").
- `tokenAbbrv`: A public string variable that represents the abbreviation of the token (e.g., "MTA").
- `totalSupply`: A public uint variable that tracks the total supply of tokens in circulation.

## Mapping Variable

- `balances`: A mapping that associates Ethereum addresses with their respective token balances. This mapping is used to keep track of how many tokens each address holds.

## Mint Function

The `mint` function allows the contract owner to mint new tokens and allocate them to a specified address. The function increases the total supply of tokens and updates the balance of the target address accordingly.

## Burn Function

The `burn` function enables token holders to burn (destroy) a certain amount of their tokens. This function decreases both the total supply of tokens and the balance of the burning address.

