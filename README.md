# Getting Started

### Option 1: Running in Remix IDE

1. Open [Remix IDE](https://remix.ethereum.org/).
2. Copy the entire code from `SimpleStorage.sol`.
3. Paste the code into a new Solidity file in Remix (e.g., `SimpleStorage.sol`).
4. Compile the contract by selecting the appropriate compiler version (e.g., `0.8.18`).
5. Deploy and interact with the contract directly in Remix.

### Option 2: Using Foundry Framework

To run this contract in a development environment, you can use the Foundry framework.

#### Prerequisites

- [Foundry](https://getfoundry.sh/) installed.

#### Instructions

1. **Initialize Foundry** (if not already initialized):

   ```bash
   forge init 
    ```

2. **Add the contract**

    Place `SimpleStorage.sol` in the `src/` folder.

3. **Compile and test**

    - Run `forge build` to compile 
    - Run `forge test` to test (optional).

4. **Run a local foundry node**

    Strat a local node with:

    ```bash
    anvil
    ```

5. **Deploy the contract to the local environment** 

    Open the new terminal and deploy with:

    ```bash 
    forge create SimpleStorage --rpc-url http://127.0.0.1:8545 --private-key 0xac0974bec3
    9a17e36ba4a6b4d238ff944bacb478cbed5efcae784d7bf4f2ff80
    ```
