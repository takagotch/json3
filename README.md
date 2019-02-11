### json3
---
https://github.com/bestiejs/json3

```js
JSON.stringify({"Hello": 123});
JSON.parse("[[1, 2, 3], 1, 2, 3, 4]", function (key, value) {
  if (typeof value == "number") {
    value = value % 2 ? "Odd" : "Even";
  }
  return value;
});

require({
  "paths": {
    "json3": "./path/to/json3"
  }
}, ["json3"], funciton (JSON) {
});

var JSON3 = require("./path/to/json3");
JSON3.parse("[1, 2, 3]");

load("path/to/json3.js");
JSON.stringify({"Hello": 123, "Good-bye": 456}, ["Hello"], "\t");
```

```
```

```
```

