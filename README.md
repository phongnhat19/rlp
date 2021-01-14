# RLP encode / decode for Deno

## Usage
```
import {encode, decode} from 'https://deno.land/x/rlp@v0.1.0/mod.ts'

const raw = ['0x01', '0x02', '0x03']
const encoded = encode(raw)
const decoded = decode(encoded)
console.log(decoded)

```