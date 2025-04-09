```markdown
# Solana Hello World – Rust Smart Contract

This project demonstrates how to build, deploy, and interact with a simple Solana smart contract using Rust. It's a basic "Hello World" program running on Solana's Devnet.

---

## Prerequisites

- [Rust](https://www.rust-lang.org/tools/install)
- [Solana CLI](https://docs.solana.com/cli/install-solana-cli-tools)
- Git
- VS Code (optional)

---

## Install Solana CLI

Solana CLI was installed using the official installation script:

```bash
sh -c "$(curl -sSfL https://release.solana.com/stable/install)"
```

*Installation screenshot:*

![Solana CLI Installed](./solana_installed.png)

---

## Clone the Hello World Example

Cloned the official example project:

```bash
git clone https://github.com/solana-labs/example-helloworld.git
cd example-helloworld
```

*Project structure:*

![Hello World Project](./hello_world.png)

---

## Build the Program

Built the smart contract with:

```bash
cargo build-bpf
```

*Build successful:*

![Build Success](./build.png)

---

## Run Local Validator

Started the local test validator to simulate a local Solana cluster:

```bash
solana-test-validator
```

*Validator running:*

![Test Validator](./test_validator.png)

---

## Configure Devnet and Deploy

Set Solana to use Devnet:

```bash
solana config set --url devnet
```

Deployed the program with:

```bash
solana program deploy dist/program/helloworld.so
```

📸 *Deployment output:*

![Program Deployed](./deploy.png)

---

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

![Wallet Address](./wallet address.png)

---

## Resources

- [Solana Docs](https://docs.solana.com/)
- [Solana CLI](https://docs.solana.com/cli)
- [Solana Hello World](https://solana.com/docs/programs/rust)

---

**Dias Zakir SE-2320**
**Anvar Tamabayev SE-2320**
**Danel Kanbakova SE-2320**  

---