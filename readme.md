## emotion-pure
`Pure.css` for emotion CSS in JS library. The original `Pure.css` is pulled from [pure-css/pure](https://github.com/pure-css/pure).

## How to use

```
npm install --save emotion-normalize
```

### CSS in JS
```jsx
import { Global } from '@emotion/core';
import pureCss from 'emotion-pure';

export const GlobalStyles = () => {
  return <Global styles={[pureCss]} />;
};
```