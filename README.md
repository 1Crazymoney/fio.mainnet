# FIO mainnet

This is the genesis file for the FIO Mainnet of https://github.com/fioprotocol/fio

## Genesis

```
{
  "initial_timestamp": "2020-03-25T00:00:00.000",
  "initial_key": "FIO7PptcpF7ai1LDgT9CvxukZ7nzM5cdeFVVDdTZeSNZLdcjYxUdk",
  "initial_configuration": {
    "max_block_net_usage": 1048576,
    "target_block_net_usage_pct": 1000,
    "max_transaction_net_usage": 524288,
    "base_per_transaction_net_usage": 12,
    "net_usage_leeway": 500,
    "context_free_discount_net_usage_num": 20,
    "context_free_discount_net_usage_den": 100,
    "max_block_cpu_usage": 200000,
    "target_block_cpu_usage_pct": 2000,
    "max_transaction_cpu_usage": 150000,
    "min_transaction_cpu_usage": 100,
    "max_transaction_lifetime": 3600,
    "deferred_trx_expiration_window": 600,
    "max_transaction_delay": 3888000,
    "max_inline_action_size": 4096,
    "max_inline_action_depth": 4,
    "max_authority_depth": 6,
    "max_ram_size": 34359738368
  }
}
```

## Chain ID
```
21dcae42c0182200e93f954a074011f9048a7624c6fe81d3c9541a614a88bd1c
```

## P2P endpoints

```
p2p-peer-address = fio.eu.eosamsterdam.net:9956 # (bp@eosamsterdam)
p2p-peer-address = fio.eosdac.io:6876 # eosDAC (bp@thedac)
p2p-peer-address = peer-fio.nodeone.network:9874 # NodeOne (fionodeonebp@nodeone)
p2p-peer-address = peer.fio.alohaeos.com:9876 # Aloha EOS (bp@alohaeos)
p2p-peer-address = peer1-fio.eosphere.io:9876 # EOSphere (bp@eosphere)
p2p-peer-address = peer2-fio.eosphere.io:9876 # EOSphere (bp@eosphere)
p2p-peer-address = fiomainnet.everstake.one:7770 # Everstake (bp@everstake)
p2p-peer-address = fio.eosrio.io:8122 # EOS Rio (br@eosrio)
p2p-peer-address = fio.acherontrading.com:9876 # Acheron Trading (bp@acherontrading)
p2p-peer-address = fiop2p.eos.barcelona:3876 # eosBarcelona (bp@eosbarcelona)
p2p-peer-address = p2p.fio.detroitledger.tech:1337 # Detroit Ledger Technologies(EOS Detroit) (eosio@detroit)
p2p-peer-address = p2p.fio.zenblocks.io:9866 # ZenBlocks (bp@zenblocks)
p2p-peer-address = p2p.blockpane.com:9876 # Blockpane
p2p-peer-address = p2p.fio.genereos.io:9876 # (bp@genereos)
p2p-peer-address = fio.greymass.com:49876 # Greymass (bp@greymass)
p2p-peer-address = fio.eosusa.news:9886 # EOSUSA (bp@eosusa)
p2p-peer-address = p2p.fioprotocol.io:3856  # Foundation for Interwallet Operability
p2p-peer-address = p2p.fio.eosargentina.io:1984 # EOS Argentina (fio@eosargentina)
p2p-peer-address = fio.cryptolions.io:7987 # CryptoLions (bp@cryptolions)
p2p-peer-address = peer.fio-mainnet.eosblocksmith.io:5090 # Blocksmith ( blocksmith@blocksmith )
p2p-peer-address = p2p.fio.services:9876 # Gandalf ( gandalf@grey )
p2p-peer-address = peer.fio.currencyhub.io:9876 # Currency Hub (bp@thecurrencyhub)
p2p-peer-address = fiop2p.eoscannon.io:6789 # EOSCannon (bp@eoscannon)
p2p-peer-address = fio.eosdublin.io:9976 # eosDublin (bp@eosdublin)
p2p-peer-address = fio.guarda.co:9976 #Guarda Wallet (bp@guardaw)
p2p-peer-address = p2p.fiosweden.org:9376 # sw/eden (bp@fiosweden)
p2p-peer-address = p2p1.fio.greeneosio.com:9876 # GreenEOSIO (bp@greeneosio)
p2p-peer-address = fiop2p.ledgerwise.io:25877 # Ledgerwise (bp@ledgerwise)
p2p-peer-address = fio-bp.dmail.co:7676 # dmail.co (bp@dmaildotco)
```

## API endpoints
  
### History v1

```
https://api.fio.detroitledger.tech
https://fio.greymass.com
https://fio.eosphere.io
https://api.fiosweden.org
https://fio.eosphere.io
https://fio.blockpane.com
```

### Hyperion

```
https://hyperion.fio.detroitledger.tech
https://api.fiosweden.org
https://fio.eosphere.io
https://fio.cryptolions.io
```

### FIO API

```
https://fio.eu.eosamsterdam.net
https://fio.eosdac.io
https://api-fio.nodeone.network:8344
https://fio.eosphere.io
https://fio.eosrio.io
https://fio.acherontrading.com
https://fio.eos.barcelona
https://api.fio.detroitledger.tech
https://api.fio.alohaeos.com
https://fio.greymass.com
https://fio.genereos.io
https://fio.eosusa.news
https://fio.eosargentina.io
https://fio.cryptolions.io
https://fio-mainnet.eosblocksmith.io
https://api.fio.currencyhub.io
https://fio.eosdublin.io
https://api.fiosweden.org
https://api.fio.greeneosio.com
https://fioapi.ledgerwise.io
https://api.fio.services
https://fio.eostribe.io
https://fio-za.eostribe.io
https://fio-bp.dmail.co
```

### FIO Testnet API

```
https://fiotestnet.blockpane.com
https://fiotestnet.greymass.com
https://test.fio.eosusa.news
https://api.fiotest.alohaeos.com
https://api.fiotest.currencyhub.io
https://testnet.fioprotocol.io
https://api.testnet.fiosweden.org
https://fio-test.eos.barcelona
https://fiotestnet.ledgerwise.io
https://fio-testnet.eosblocksmith.io
https://fio-bp.dmail.co:7777
```

### Snapshots

```
https://snapshots.eosphere.io
https://fio.snapshots.eossweden.org
https://snap.blockpane.com
```
