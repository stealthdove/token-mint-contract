-contract deploy
npx hardhat run scripts/deploy.js --network [network]

-contract verify
npx hardhat verify --contract contracts/MyBirdTestToken.sol:MyBirdTestToken --network sepolia 0xE8c59b24729975033A656a17411b6F80805Fc6Da "mybirdtest" "OCEXB" 18 

-deployed address
0xE8c59b24729975033A656a17411b6F80805Fc6Da

-run bot
npm start
