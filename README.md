## About

### Description

Implementation of DAO. Built using OpenZeppelin Wizard

### Purpose

Part of Advanced Foundry course from Cyfrin Updraft and as submodule in [appropriate repository](https://github.com/kuzminklk/cyfrin-updraft)

### Technologies

Development: Visual Studio Code  
Programming language: Solidity  
Environment: Foundry  
Network: Ethereum  
Smart-contracts: OpenZeppelin  
Formatting: “.editorconfig”, “.vscode/…”, Foundry, Prettier  

## State

### Status

Finished, tested locally, but didn't deploy to testnet due issue with deployment

### Path

1. Finish course materials
2. Try to create deploy script and deploy to testnet, meet an issue (contract size limit and mess with “msg.sender” and “tx.origin”)

### To-dos

- Solve deploy problems in Foundry
- Rebuild project in Hardhat with more clear scripts

### Deployments

Didn't deploy for now. Script doesn't work correctly (meet contract size limit issue and mess with “msg.sender” and “tx.origin”)

## Usage

### Set Up

Install Foundry dependencies: `forge install`

### Use

Basic Foundry commands: `forge build`, `forge test`  
Other appropriate commands in `./commands.sh`
