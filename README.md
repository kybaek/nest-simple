### directory

```bash
+- nest-simple
+- model

### Setup
* clone model
```bash
git clone https://github.com/kybaek/model.git
```

* install dependencies
```bash
yarn install
```

### Start nest

```bash
yarn start
```

* error
```
const secp256k1_1 = require("@noble/secp256k1");
Error [ERR_REQUIRE_ESM]: require() of ES Module nest-simple/node_modules/model/node_modules/@noble/secp256k1/index.js from nest-simple/node_modules/model/lib/common/index.js not supported.
```

### Upgrade model

```bash
yarn upgrade model
```

```