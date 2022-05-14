
- wasm-pack: This is a Rust tool for building Rust-generated WebAssembly code

- wasm-bindgen gives you the capability to communicate between WebAssembly and JavaScript

- web-sys contains a large number of pre-created bindings.
```
[dependencies.web-sys]
version = "0.3.55"
features = [
  "console" ,
  'CanvasRenderingContext2d',
  'Document',
  'Element',
  'HtmlCanvasElement',
  'Window']
```

## Rust webpack Tempalte
https://github.com/rustwasm/rust-webpack-template


## Setup
```
cd app

npm init rust-webpack

npm i


```

Install wasm-pack
```
 curl https://rustwasm.github.io/wasm-pack/installer/init.sh -sSf | sh

```


## Run
```
  npm run start
```