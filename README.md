Rustの`cql!`マクロ内の文字列リテラルのみにCQLシンタックスハイライトを適用します。<br>
Applies CQL syntax highlighting only to string literals inside Rust's `cql!` macro.

```rust
macro_rules! cql {
    ($query:expr) => {
        $query
    };
}
```

![Image](sample.png)