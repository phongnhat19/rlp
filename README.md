# RLP encode / decode for Deno

## Usage
```
import {encode, decode} from 'https://raw.githubusercontent.com/phongnhat19/rlp/master/mod.ts'

const raw = ['0x01', '0x02', '0x3']
const encoded = encode(raw)
const decoded = decode(encoded)
console.log(decoded)

```