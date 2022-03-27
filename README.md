# Go Bindings for Ethereum Contracts

## ERC721
Contract: v4.5.0 OpenZeppelin/openzeppelin-contracts/contracts/token/erc721
Solidity: 0.8.12+commit.f00d7308.Darwin.appleclang
Abigen:   1.10.16-stable
Go:       go1.17.8 darwin/amd64

          `solc --abi ERC721.sol -o build`
          `abigen --abi=./build/ERC721.abi --pkg=erc721 --out=ERC721.go`

## ERC20
Contract: v4.5.0 OpenZeppelin/openzeppelin-contracts/contracts/token/erc20
Solidity: 0.8.12+commit.f00d7308.Darwin.appleclang
Abigen:   1.10.16-stable
Go:       go1.17.8 darwin/amd64

          `solc --abi ERC20.sol -o build`
          `abigen --abi=./build/ERC20.abi --pkg=erc20 --out=ERC20.go`
