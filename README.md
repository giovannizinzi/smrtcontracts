### Forked for my first "ground-up" smart contract on Solana
Following this guide: https://paulx.dev/blog/2021/01/14/programming-on-solana-an-introduction/
Hope to build on top of this project. Should lay out some of the primitives. Next need to learn anchor

### Environment Setup
1. Install Rust from https://rustup.rs/
2. Install Solana v1.6.2 or later from https://docs.solana.com/cli/install-solana-cli-tools#use-solanas-install-tool

### Build and test for program compiled natively
```
$ cargo build
$ cargo test
```

### Build and test the program compiled for BPF
```
$ cargo build-bpf
$ cargo test-bpf
```
