---
layout: single 
title: rust_for_fun
categories: Dev
tags: [Rust, Test]
---

### installation
1. `curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh`
2. rustup update
3. (done)
   
---

### data tpyes & variables
  > C-like

- let, mut
- Immutable by default

```rust
let whole_num = 1;
let character = 'c';
let string = "String";
```

### functions
```rust
//   name      params      return_type
fn fn_name(a:i64, b:i64) -> i64 {
//   body
    a + b
}
```

### macro
>  !!! 

```rust
let my_name = "Hyuk";
println!("hihi, ");
println!("{:?}", my_name)
```

