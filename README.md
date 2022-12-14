**Author**: Kunaal Gupta

**Programming Lanaguage**: Solidity

**Description**: An Ethereum-based dApp using Solidity smart contract which allows multiple parties to involve in bidding on various digital assets

**Concepts**:
* EThereum Blockchain
* Soldity Programming Language
* Smart Contracts
* DApp
* Transaction
* Assets transfer

**Included Files**: 
 * .deps
 * .git
 * artifacts
 * contracts
 * scripts
 * swarm
 * tests
 * Auction
 * README
 

About Files
 * The 'scripts' folder has four typescript files which help to deploy the 'Storage' contract using 'web3.js' and 'ethers.js'.
 * The 'contracts' folder has three contracts with increasing levels of complexity.
 * In the 'tests' folder there is  one Solidity test file for 'Ballot' contract & one JS test file for 'Storage' contract.
 * For the deployment of any other contract, just update the contract's name from 'Storage' to the desired contract and provide constructor arguments accordingly in the file `deploy_with_ethers.ts` or  `deploy_with_web3.ts` 

**Running Instructions** :
To run a script, right click on file name in the file explorer and click 'Run'. Remember, Solidity file must already be compiled. Output from script will appear in remix terminal. Please note, require/import is supported in a limited manner for Remix supported modules. For now, modules supported by Remix are ethers, web3, swarmgw, chai, multihashes, remix and hardhat only for hardhat.ethers object/plugin. For unsupported modules, an error like this will be thrown: '<module_name> module require is not supported by Remix IDE' will be shown.

**Software Used**:
 * Remix IDE

**Acknowledgments**: 
 * Etherium Docs
 * Solidity Documentaion
 * Remix’s documentation

**Github Profile**: https://github.com/kunaal-gupta

**Feedback**: If you have any feedback or issue(s), please reach out to me at kunaalgupta@hotmail.com
