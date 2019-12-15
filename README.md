This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

### CRA Usage (CSR)
```
import React from 'react';
import Claps from '@wismim/react-claps';
export default function () {
    return <Claps />
}
```

### Usage in NEXT JS (SSR)
```
const Claps = dynamic(() => import('@wismim/react-claps'))
```
