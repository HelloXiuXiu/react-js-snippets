# Sublime Text React and JS Snippets!

To use a snippet type the shortcut and press Tab.
Use Tab to change $1, $2, etc. statements one by one.

---

### rfc

```js
import React from 'react';

export const ${1:${file_name}} = () => {
  return (
    ${2:<div>Hello</div>}
  )
}
```

### ael

```js
${1:window}.addEventListener(${2:'click'}), ${3:'handleClick'})
```

### rel

```js
${1:window}.removeEventListener(${2:'click'}), ${3:'handleClick'})
```
