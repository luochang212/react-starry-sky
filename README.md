# React Starry Sky
### Introduction
a lovely and easy-to-use React background component develop for my girlfriend!💕
### Usage
```
npm i react-starry-sky -S
```

```css
.wrapper {
  position: relative;
  height: 100vh;
}
```

```js
import React from 'react';
import ReactDOM from 'react-dom';
import Starry from 'react-starry-sky';

import './styles/index.css';

const Demo = () => (
  <Starry className="wrapper">
    <div>
      SSH 💕 WYQ
    </div>
  </Starry>
);

ReactDOM.render(<Demo />, window.document.getElementById('app'));
```

### Preview
https://sl1673495.github.io/react-starry-sky/

### Development

```dev
npm i
npm run dev
```

Navigate to `http://localhost:8888`

### Build

```lib
npm run build:lib
```

```demo
npm run build:demo
```


Compiled assets files will be in `build` folder
