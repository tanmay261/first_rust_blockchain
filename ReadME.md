Module 2 Assignment.

Dependencies

chrono :- the date and time package for rust

serde :- ser stands dor serialising , de stands for deserialising Rust data structures generically

serde_json:- ser and de for JSON specifically

sha2 :- includes cryptographic algos , Sha224, Sha256, Sha512_224, Sha512_256, Sha384, and Sha512.

Issues

Under the blockchain.rs

1. #[derive(Debug,Clone)] "Clone" is added in the macro , additional to the tutorial

2. add_block function's nonce parameter is not being accepted by the function , so had to remove it

3. add_block function's new_block variable had to be made mutable
