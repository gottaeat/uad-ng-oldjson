uad-ng 0.6.2
============
```sh
       RUSTFLAGS="-Ctarget-cpu=x86-64 -Copt-level=3"
export RUSTFLAGS="${RUSTFLAGS} -Cdebuginfo=0 -Cdebug-assertions=off"

cargo fetch --locked
cargo build --release --frozen --no-default-features --features no-self-update
```
