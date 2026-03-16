# SHA512.js
SHA-512, SHA-384, SHA-512/224, SHA-512/256 ハッシュ関数のJavaScript実装です。ブラウザやDenoでUTF-8エンコーディングをサポートしています。

## 機能
- SHA-512, SHA-384, SHA-512/224, SHA-512/256 ハッシュ関数の提供
- UTF-8エンコーディングのサポート
- 配列バッファ、整数配列出力のサポート
- ストリーミングAPI(update)のサポート
- HMACのサポート
- クローニングのサポート

## 使い方
```js
import { SHA512 } from "https://code4fukui.github.io/SHA512/SHA512.js";

console.log(SHA512.digest("Message to hash"));
```

## ライセンス
MITライセンスで公開されています。