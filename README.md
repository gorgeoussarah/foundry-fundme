
# FundMe DApp

[![Foundry](https://img.shields.io/badge/Built%20with-Foundry-FF6943?logo=ethereum)](https://getfoundry.sh)
[![Solidity](https://img.shields.io/badge/Solidity-0.8.23-363636?logo=solidity)](https://soliditylang.org)
[![Chainlink](https://img.shields.io/badge/Chainlink-Price%20Feeds-blue?logo=chainlink)](https://chain.link)
[![Tests](https://img.shields.io/github/actions/workflow/status/gorgeoussarah/foundry-fundme/test.yml?label=tests)](https://github.com/gorgeoussarah/foundry-fundme/actions)
[![Alchemy](https://img.shields.io/badge/Alchemy-RPC%20Provider-blueviolet)](https://www.alchemy.com)
[![Etherscan](https://img.shields.io/badge/Etherscan-Contract%20Verification-brightgreen)](https://etherscan.io/address/0xe7f1725E7734CE288F8367e1Bb143E90bb3F0512)

---

## Project Description

FundMe is a **crowdfunding smart contract** built with Solidity and Foundry. It allows users to:

- Fund the contract with ETH, respecting a minimum USD amount via Chainlink price feeds  
- Withdraw funds (owner-only)  
- Easily track contributors and their contributions  

The project uses **Foundry** for development and testing, **Alchemy** as the RPC provider, and **Etherscan** for contract verification.

---

## Features

- Accept ETH funding from multiple users  
- Minimum USD contribution enforced via Chainlink  
- Owner-only withdraw function  
- Fully tested with Foundry  
- Scripts for deployment, funding, and withdrawal  

---

## Installation & Usage

1. Clone the repository:

```bash
git clone https://github.com/gorgeoussarah/foundry-fundme.git
cd foundry-fundme

## Usage

```bash
forge build
forge test
forge script script/DeployFundMe.s.sol --broadcast
