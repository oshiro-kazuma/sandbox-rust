sandbox-rust
==============

setup for mac
```
brew install rust
brew install rustup
RUSTUP_INIT_SKIP_PATH_CHECK=yes rustup-init
```

run
```
cargo run
```


Add to .zshrc
```
export CARGO_HOME="$HOME/.cargo"
export PATH="$CARGO_HOME/bin:$PATH"
```
