# OurToken Project

Welcome to the **OurToken Project**, a simple ERC20 token implementation using the Foundry development environment and OpenZeppelin contracts. This repository provides a basic setup to get you started with smart contract development, testing, and deployment.

## Project Organization

This repository follows a standard structure provided by Foundry:

- **`src/`**: Contains the main Solidity contract files.
  - `OurToken.sol`: The ERC20 token contract.
- **`script/`**: Holds the deployment scripts.
  - `DeployOurToken.s.sol`: Script to deploy the `OurToken` contract.
- **`test/`**: Includes test files for smart contracts.
  - `OurTokenTest.t.sol`: Unit tests for the `OurToken` contract.

## Getting Started

### Prerequisites

Ensure you have the following installed on your system:

- **Foundry**: A blazing-fast, portable, and modular toolkit for Ethereum application development written in Rust.

### Installation

1. **Initialize Foundry**:

   ```bash
   forge init
   ```

2. **Install OpenZeppelin Contracts**:
   ```bash
   forge install openzeppelin/openzeppelin-contracts@v5.0.2 --no-commit
   ```

### Commands

Below are some of the common commands you will use in this repository:

- **Compile Contracts**:

  ```bash
  forge build
  ```

- **Run Tests**:

  ```bash
  forge test
  ```

- **Deploy Contracts**:
  Deployment is handled by the script in the `script/` directory. Use the following command to run the deployment script:

  ```bash
  forge script script/DeployOurToken.s.sol --broadcast
  ```

- **Format Code**:

  ```bash
  forge fmt
  ```

- **Lint Code**:
  ```bash
  forge fmt --check
  ```

## References

- **ERC20 Standard**: Learn more about the ERC20 token standard [here](https://eips.ethereum.org/EIPS/eip-20).
- **Foundry Documentation**: For more details on Foundry, visit the [Foundry Book](https://book.getfoundry.sh/).

## License

This project is licensed under the MIT License. See the LICENSE file for details.
