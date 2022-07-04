# Weekend Project #2

- Structure scripts to
  - Deploy
  - Query proposals
  - Give vote right passing an address as input
  - Cast a vote to a ballot passing contract address and proposal as input and using the wallet in environment
  - Delegate my vote passing user address as input and using the wallet in environment
  - Query voting result and print to console
- Publish the project in Github
- Run the scripts with a set of proposals, cast and delegate votes and inspect results
- Write a report detailing the addresses, transaction hashes, description of the operation script being executed and console output from script execution for each step (Deployment, giving voting rights, casting/delegating and querying results).
- (Extra) Use TDD methodology

### Step 1 Deploy Contracts

#### Token
- Make a token contract with token name "MyToken"
- To run script `yarn ts-node --files ./scripts/Token/deployment.ts`
- Which gives us a contract Address <a href="https://goerli.etherscan.io/address/0xe95E54Bc0eeC8d3c51B0486d127ADf93Edd4e6bc" target="_blank">0xe95E54Bc0eeC8d3c51B0486d127ADf93Edd4e6bc</a>
#### Custom Ballot
- Make a contract with proposals as parameters in our case the parameters are ("Samosa","Kebab","Jalebi")
- To run script `yarn ts-node --files ./scripts/Ballot/deployment.ts Samosa Kebab Jalebi`
- Which gives us a contract Address <a href="https://goerli.etherscan.io/tx/0xd2a9ed6ff19b2011d5cc8608ec781858b6fdfed9f71c689a176d51b73af97c3d" target="_blank">0x63f3D511472DBCaA8d28C89d67273d6eA83C34C4</a>


### Step 2 Minting tokens


### Step 3 Creating a ballot


### Step 4 Give right to vote


### Step 5 Delegate the vote


### Step 6 Cast a vote


### Step 7 Query voting results

- 

