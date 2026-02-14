# RomanNumberConverter

## Using in the Node console

Start the Node REPL in this folder. You can either manually paste the require line or preload it:

```powershell
node
```

```js
const { convertToRoman } = require("./RomanNumberConverter");
convertToRoman(42);
```

Or start the REPL with the module preloaded:

```powershell
node -i -e "const { convertToRoman } = require('./RomanNumberConverter');"
```

Then call it directly:

```js
convertToRoman(42);
```