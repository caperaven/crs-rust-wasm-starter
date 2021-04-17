# CRS Rust WASM Starter

## Introduction
This project is a template for starting Rust web assembly libraries.  
This project uses standard ES Modules thus no bundlers.

This project assumes you have rust installed and dependencies like wasm-pack.  
If you don't have wasm-pack installed you can do so using
```
cargo install wasm-pack
```

Remember to update the Cargo.toml file in the rust folder with your project details.

## Building the project
```
wasm-pack build rust/ --target web --out-dir ../bin
```

The package.json file contains a script that will build it for you, should you prefer that.

## Getting started links
https://rustwasm.github.io/wasm-bindgen/introduction.html  
https://rustwasm.github.io/docs/wasm-pack/  
https://developer.mozilla.org/en-US/docs/WebAssembly/Rust_to_wasm  

## Other links
https://github.com/rustwasm/wasm-bindgen