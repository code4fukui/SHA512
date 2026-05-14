# SHA512.js

ブラウザおよびDeno向けのUTF-8エンコーディングをサポートする、JavaScript ESモジュール用のシンプルなSHA-512、SHA-384、SHA-512/224、SHA-512/256ハッシュ関数です。

## 特徴
- SHA-512、SHA-384、SHA-512/224、SHA-512/256をサポート
- UTF-8エンコーディングをサポート
- ストリーミングAPIをサポート
- ブラウザ、Deno、Node.jsをサポート

## 使い方
以下のように使用できます:
```js
import { SHA512 } from "https://code4fukui.github.io/SHA512/SHA512.js";

console.log(SHA512.digest("Message to hash"));
```

## ライセンス
MITライセンス — 詳細は[LICENSE](LICENSE)を参照してください。
