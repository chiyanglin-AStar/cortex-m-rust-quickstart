### cortex-M rust quickstart steps

    cargo install cargo-generate

    cargo generate --git https://github.com/chiyanglin-AStar/cortex-m-rust-quickstart

    cd app/

    rustup target add thumbv7m-none-eabi

    cargo build

    cargo build --example hello

    sudo apt-get install qemu-system-arm

    qemu-system-arm   -cpu cortex-m3   -machine lm3s6965evb   -nographic   -semihosting-config enable=on,target=native   -kernel target/thumbv7m-none-eabi/debug/examples/hello

#### doc and rustc command reference 

-[Doc](https://doc.rust-lang.org/stable/embedded-book/intro/index.html)
