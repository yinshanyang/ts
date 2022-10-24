```json
"scripts": {
  "start": "ts-node src/index.ts",
  "test": "ts-node node_modules/tape/bin/tape src/**/*.test.ts",
  "test:watch": "nodemon --exec npm test --ext ts --ignore node_modules/"
}
```
