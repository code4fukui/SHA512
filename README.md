# SHA512.js

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A simple SHA-512, SHA-384, SHA-512/224, SHA-512/256 hash functions for JavaScript ES modules that supports UTF-8 encoding for browsers and Deno.

## Features
- Supports SHA-512, SHA-384, SHA-512/224, SHA-512/256
- UTF-8 encoding support
- Streaming API support
- Browser, Deno, and Node.js support

## Usage
You could use like this:
```js
import { SHA512 } from "https://code4fukui.github.io/SHA512/SHA512.js";

console.log(SHA512.digest("Message to hash"));
```

## License
MIT License — see [LICENSE](LICENSE).