# Foundry Simple Storage

This project was made following along with Patrick Collins' Foundry course.

### Notes

- cmd+shift+v to preview markdown
- forge is used for interacting and deploy contracts
  - forge script script/DeploySimpleStorage.s.sol --rpc-url $RPC_URL --private-key $PRIVATE_KEY --broadcast
- cast is used for interacting with deployed contracts
  - cast --to-base 0x714e1 dec
  - cast send $CONTRACT_ADDRESS "FUNCTION(PARAMETER_DATA_TYPE)" ARGUMENT
  - cast call $CONTRACT_ADDRESS "FUNCTION()"
