# rust-playground
Playground for Rust

# 参考
https://doc.rust-jp.rs/the-rust-programming-language-ja/1.6/book/README.html


# 導入
```
$ curl https://sh.rustup.rs -sSf | sh
...
info: default toolchain set to 'stable'

  stable installed - rustc 1.42.0 (b8cedc004 2020-03-09)


  Rust is installed now. Great!

```

```
$ source ~/.zshrc
```

# Cargo

Rustのパッケージマネージャ。
Toml形式のCargo.tomlを記述してビルド。

```
[package]

name = "hello_world"
version = "0.0.1"
authors = [ "あなたの名前 <you@example.com>" ]
```

```
$ cargo build
  Compiling hello_world v0.0.1 (/Users/otajisan/github/rust-playground/hello-cargo)
   Finished dev [unoptimized + debuginfo] target(s) in 2.17s

```

```
$ cargo run
  Finished dev [unoptimized + debuginfo] target(s) in 0.00s
   Running `target/debug/hello_world`
 Hello, world!
```

新規プロジェクト作成

```
$ cargo new hello_world --bin
```

```
$ cargo new my-project --bin
   Created binary (application) `my-project` package
```



