# EOS System Contracts

## Release Candidate `v3.1.0`

- [Branch `release/3.1` (last commit `a408ba6`)](https://github.com/eosnetworkfoundation/eos-system-contracts/releases/tag/v3.1.0)

## Amendments

- [EOS User Agreement (EUA)](https://github.com/EOS-Mainnet/governance/blob/master/eosio.system/eosio.system-clause-constitution-rc.md)
- [EOS 42 `regproducer` update](https://github.com/eos42/regproduceupodate/blob/master/eosio.system-regproducer-rc.md)

## CDT `3.0.0`

- [Branch `release/3.0` (last commit `ca04970`)](https://github.com/AntelopeIO/cdt/releases/tag/v3.0.0)

**Install**

```
$ wget https://github.com/AntelopeIO/cdt/releases/download/v3.0.0/cdt_3.0.0_amd64.deb
$ sudo apt install ./cdt_3.0.0_amd64.deb
```

**Version**

```bash
$ cdt-cpp --version
cdt-cpp version 3.0.0
```

**Build**

```bash
$ git clone https://github.com/eosnetworkfoundation/eos-system-contracts.git
$ cd eos-system-contracts
$ ./build.sh
```

## SHA256 Checksum

```bash
$ shasum -a 256 eosio.system.wasm
a74fe8ee0baa77aa57e906efff021eb32fe099c7a1b349693e07c49bc188df30  eosio.system.wasm
```
