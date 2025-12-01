# Compressor.js

JavaScript image compressor.

## Installation

```bash
npm install compressorjs
```

## Usage

```javascript
import Compressor from 'compressorjs';

new Compressor(file, {
  quality: 0.6,
  success(result) {
    console.log(result);
  },
  error(err) {
    console.log(err.message);
  },
});
```

## License

MIT
