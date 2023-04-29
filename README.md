# [Introdução a linguagem Rustlang | Aprenda Rust | 01](https://youtu.be/zWXloY0sslE)

## Ambiente Rust Online

https://play.rust-lang.org/

https://replit.com/

## Instalando Rust
```bash
sudo apt install build-essential curl micro
```

https://rustup.rs/

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

1) Proceed with installation (default)

To configure your current shell, run:
```bash
source "$HOME/.cargo/env"
```

## Compilando com Rustc
```bash
micro hello.rs
```

```rust
fn main() { // função entry point
	println!("Hello World") // macro !
}
```

```bash
rustc hello.rs
```

```bash
./hello
```
