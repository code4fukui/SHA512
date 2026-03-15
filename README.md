# SHA512.js
A simple SHA-512, SHA-384, SHA-512/224, SHA-512/256 hash functions for JavaScript ES modules supports UTF-8 encoding for browsers and Deno.

## Demo
[SHA512 Online](http://emn178.github.io/online-tools/sha512.html)  
[SHA384 Online](http://emn178.github.io/online-tools/sha384.html)  
[SHA512/256 Online](http://emn178.github.io/online-tools/sha512_256.html)  
[SHA512/224 Online](http://emn178.github.io/online-tools/sha512_224.html)  

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
The project is released under the [MIT license](http://www.opensource.org/licenses/MIT).