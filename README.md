<h1 align="center"><code>builtin-check.js</code></h1>

<p align="center">Validate if a string is a Node.js built-in module</p>

## ⚙️ Installation

```terminal
npm i builtin-check
```

## 📖 Usage

#### ▸ Import

```js
// ES6
import builtinCheck from "builtin-check";

// commonjs
const builtinCheck = require("builtin-check");
```

#### ▸ Check

```js
builtinCheck("fs");
// True

builtinCheck("concall");
// False
```

---

[Support me on Patreon](https://www.patreon.com/axorax) — 
[Check out my socials](https://github.com/axorax/socials)