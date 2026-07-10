# NobleSwap Contracts

Collection of Solidity contracts that support the NobleSwap ecosystem, including exchange, liquidity, and supporting protocol components. The repository is organized as independent Hardhat projects beneath `contracts/`.

## Layout

- `contracts/core/` — core exchange protocol contracts
- `contracts/periphery/` — routers and peripheral contracts
- `test/` — contract-level tests

## Development

Install dependencies with `npm install`, then use Hardhat from the relevant project configuration to compile and run tests. Review each project's Solidity version and configuration before making changes.

## Security

These contracts are financial infrastructure. Changes require thorough testing, review of inherited upstream behavior, and an appropriate security assessment before production use.

