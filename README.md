# rust-echo-client

Rustで挑戦ネットワークプログラミングコードで理解するTCP/IP
- Software Design (ソフトウェアデザイン) 2021年1月号

## 構成
```
$ tree
.
├── Cargo.lock
├── Cargo.toml
├── README.md
└── src
    └── main.rs
```

## 使い方
```
# エコークライアントのビルドと実行
/Users/yuji.hanada/.cargo/bin/cargo run --color=always
    Finished dev [unoptimized + debuginfo] target(s) in 0.00s
     Running `target/debug/rust-echo-client`
start echo client...
rust # エコーサーバへ送信
rust # エコーサーバからの受信
```