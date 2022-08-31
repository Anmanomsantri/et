### Note
If this reprository is useful to you in in any shape or form please give it a star.

### How it works
It generates random private keys / seeds and then takes drains funds from them

### Prerequisites
1. Install [rust](https://www.rust-lang.org/tools/install)
2. Install windows [tooclahin](https://rust-lang.github.io/rustup/installation/windows.html)

### Setup
1. Goto [constants.rs](https://github.com/RadonCoding/ethereum-stealer/blob/main/src/constants.rs#L5) and replace the address with your own
2. Change the `ENDPOINT` in [constants.rs](https://github.com/RadonCoding/ethereum-stealer/blob/main/src/constants.rs#L2)
3. Run `cargo build --release --target=x86_64-pc-windows-msvc`

### Contributing
1. Fork it
2. Create your branch (`git checkout -b my-change`)
3. Commit your changes (`git commit -am 'changed something'`)
4. Push to the branch (`git push origin my-change`)
5. Create new pull request

### Disclaimer
You will most likely not get anything from this since his project was made for fun.

This project is based on https://tms-dev-blog.com/build-a-crypto-wallet-using-rust
