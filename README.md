# ntext

A rust library to get numbers (u32) as words

`12345` -> `twelvethousandthreehundredfortyfive`  
`81123` -> `eightyonethousandonehundredtwentythree`  
`12` -> `twelve`

Add to cargo.toml

```toml
[dependencies]
ntext = { git = "https://github.com/uttarayan21/ntext" }
```

Example program

```rust
extern crate ntext;
use ntext::to_text;
fn main() {
    println!("{}",to_text(12345));
}
```

which should output  
`twelvethousandthreehundredfortyfive`

I will probably add formatting the text later