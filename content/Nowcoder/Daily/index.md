# 格式

## 关于 JavaScript V8

```javascript
while ((input = readline())) {
  solve(input);
}
function solve(input) {
  console.log(input);
}
```

## 关于 JavaScript Node

```javascript
const readline = require('readline');

const rl = readline.createInterface({
  input: process.stdin,
  output: process.stdout
});

rl.on('line', function (line) {
  console.log(line);
});
```
