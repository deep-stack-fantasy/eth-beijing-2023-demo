# eth-beijing-2023-demo

## Demo files

[Remix IDE with DSF Solidity Compiler (solijson.js)](https://remix.ethereum.org/#lang=en&optimize=false&runs=200&evmVersion=null&version=https://ec2-35-88-251-70.us-west-2.compute.amazonaws.com:8899/eth-beijing-demo/soljson.js).

[Example Solidity file](https://ec2-35-88-251-70.us-west-2.compute.amazonaws.com:8899/eth-beijing-demo/test100.sol)

Note: The compiler file is ~8 MB, which requires a relatively long time to load. Please manually add the URL of [DSF Solidity Compiler (solijson.js)](https://ec2-35-88-251-70.us-west-2.compute.amazonaws.com:8899/eth-beijing-demo/soljson.js) in Remix IDE if there is a network failure.

Note: our modified compiler is still struggling with `invalid jump` issue. Currently the compiler can successfully generate bytecodes, but these codes are unable to correctly run on our modified EVM. We are working on this issue.

## Video
https://youtu.be/AiOXepNjYzw

## Slides and Codes
https://github.com/orgs/deep-stack-fantasy/repositories
