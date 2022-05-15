<div align="center">

  <h1><code>Wasm Game of Life</code></h1>

  <strong>My output from following the Rust-Wasm Tutorial for using <a href="https://github.com/rustwasm/wasm-pack">wasm-pack</a>.</strong>

  <h3>
    <a href="https://rustwasm.github.io/docs/book/">Tutorial</a>
  </h3>

  <sub>Built with 🦀🕸 by <a href="https://rustwasm.github.io/">The Rust and WebAssembly Working Group</a></sub>
</div>

## About

This Repository is from my follow-through of the Rust-Wasm tutorial. Testing doesn't work on my system, likely because my username hase a space in it. Unsure. The below is for the template used.

[tutorials]: https://rustwasm.github.io/docs/wasm-pack/tutorials/index.html
[template-docs]: https://rustwasm.github.io/docs/wasm-pack/tutorials/npm-browser-packages/index.html

## 🚴 Usage

### This will be available to play with/enjoy on my website when it is done. If you want to have your own copy of the wasm-pack template, use the code below.

```
cargo generate --git https://github.com/rustwasm/wasm-pack-template.git --name my-project
cd my-project
```

### 🛠️ Build with `wasm-pack build`

```
wasm-pack build
```

## 🔋 Batteries Included

* [`wasm-bindgen`](https://github.com/rustwasm/wasm-bindgen) for communicating
  between WebAssembly and JavaScript.
* [`console_error_panic_hook`](https://github.com/rustwasm/console_error_panic_hook)
  for logging panic messages to the developer console.
* [`wee_alloc`](https://github.com/rustwasm/wee_alloc), an allocator optimized
  for small code size.
