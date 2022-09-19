# Curso de Blockchain da DIO

## Projeto node-create-wallet
Projeto inicial para criação de carteira com endereço e chave privada usando:

- NodeJS (16)
- Bip32
- Bip39
- Bitcoinjs-lib

## - Para executar
- OBS: Estar conectado à rede para criação da carteira na rede 'testnet'

### Na raiz do projeto executar os comandos:

```
npm install
```

Após instaladas as dependências do projeto, executar:

```
node create-wallet.js
```

#### O resultado da criação da carteira será mostrado no terminal com endereço e chave privada da carteira


## Projeto remix-contract-deploy
Projeto para deploy de um contrato de moeda usando a Remix IDE usando:

- Solidity
- Padrão ER20
- Ganache
- Metamask

### - Para executar

- Abrir o Ganache para disponibilizar carteiras localmente para teste
- Conectar o Metamask à rede local do Ganache
- Fazer o deploy do código deste repositório na Remix IDE (https://remix.ethereum.org/)
- Interagir com a moeda-contrato e carteiras no Metamask da rede do Ganache

#### O resultado é a possibilidade de transações pelo Metamask escrevendo na rede do Ganache


