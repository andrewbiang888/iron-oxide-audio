<div align="center">

  <h1><code>iron-oxide-audio</code></h1>

  <strong>An audio experiment using the JavaScript [Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API) in Rust, compiled to WebAssembly, and used in . . . JavaScript</strong>

</div>

## About

This repo used [`wasm-pack`](https://rustwasm.github.io/docs/wasm-pack) for initial setup.

## Generic `wasm-pack` reminders

### 🛠️ Build with `wasm-pack build`

```
wasm-pack build
```

### 🔬 Test in Headless Browsers with `wasm-pack test`

```
wasm-pack test --headless --firefox
```

### 🎁 Publish to NPM with `wasm-pack publish`

```
wasm-pack publish
```

## 🔋 Batteries Included

* [`wasm-bindgen`](https://github.com/rustwasm/wasm-bindgen) for communicating
  between WebAssembly and JavaScript.
* [`console_error_panic_hook`](https://github.com/rustwasm/console_error_panic_hook)
  for logging panic messages to the developer console.
* [`wee_alloc`](https://github.com/rustwasm/wee_alloc), an allocator optimized
  for small code size.
