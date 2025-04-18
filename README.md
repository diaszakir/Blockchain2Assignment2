# Solana Hello World – Rust Smart Contract

This project demonstrates how to build, deploy, and interact with a simple Solana smart contract using Rust. It's a basic "Hello World" program running on Solana's Devnet.

## Prerequisites

- [Rust](https://www.rust-lang.org/tools/install)
- [Solana CLI](https://docs.solana.com/cli/install-solana-cli-tools)
- Git
- VS Code (optional)

## Install Solana CLI

Solana CLI was installed using the official installation script:

```bash
sh -c "$(curl -sSfL https://release.solana.com/stable/install)"
```

*Installation screenshot:*

![Solana CLI Installed](./screenshots/solana_installed.png)

## Hello World Example

*Project structure:*

![Hello World Project](./screenshots/hello_world.png)

## Build the Program

Built the smart contract with:

```bash
cargo build-sbf
```

*Build successful:*

![Build Success](./screenshots/build.png)

## Configure Devnet and Deploy

Set Solana to use Devnet:

```bash
solana config set --url https://api.devnet.solana.com
```

Deployed the program with:

```bash
solana program deploy ./target/deploy/hello_world.so
```

📸 *Deployment output:*

![Program Deployed](./screenshots/deploy.png)

## Wallet & Program Info

Wallet address:

```
QSzKtCs9qhAxrMhjv5wtsFV5Uf5xLrbGZAUwsRT22BP
```

Program ID:

```
EQWVh1trpTorimfTwjbhBe2ZNd8eqVJZuHLPcfv66vSL
```

*Wallet screenshot:*

![Wallet Address](./screenshots/wallet_address.png)

## Resources

- [Solana Docs](https://docs.solana.com/)
- [Solana CLI](https://docs.solana.com/cli)
- [Solana Hello World](https://solana.com/docs/programs/rust)

**Dias Zakir SE-2320**

**Anvar Tamabayev SE-2320**

**Danel Kanbakova SE-2320**  
