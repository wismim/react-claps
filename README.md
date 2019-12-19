## Slim & sleak Medium like Claps component in react for client side.

### CRA Usage (CSR)
```
import React from 'react';
import Claps from '@wismim/react-claps';
export default function () {
    return <Claps maxCount={10000} count={0} countTotal={0} onCountChange={({ count, countTotal }) => console.log(count, countTotal)}/>
}
```

### Usage in NEXT JS (SSR)
```
const Claps = dynamic(() => import('@wismim/react-claps'));
export default function () {
    return <Claps maxCount={10000} count={0} countTotal={0} onCountChange={({ count, countTotal }) => console.log(count, countTotal)} />
}
```
