# hello-zokrates

![ZoKrates](https://avatars.githubusercontent.com/u/38394829?s=200&v=4)

ZoKrates is a toolbox for zkSNARKs on Ethereum. It helps you use verifiable computation in your DApp, from the specification of your program in a high level language to generating proofs of computation to verifying those proofs in Solidity

[ZoKrates docs](https://zokrates.github.io/introduction.html)

## Use

```sh
# compile
zokrates compile -i root.zok
# perform the setup phase
zokrates setup
# execute the program
zokrates compute-witness -a 337 113569
# generate a proof of computation
zokrates generate-proof
# export a solidity verifier
zokrates export-verifier
# or verify natively
zokrates verify
```
