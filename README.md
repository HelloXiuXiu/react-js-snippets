# Sublime Text Snippets (React + Redux and JS)! 

To use a snippet type the shortcut and press Tab.
Use Tab to change $1, $2, etc. statements one after another.

List of snippets:

## React + Redux

### rfc
```js
import React from 'react';

export const ${1:${file_name}} = () => {
  return (
    ${2:<div>Hello</div>}
  )
}
```

### st
```js
const [${1:'kek'}, set${1:'Kek'}] = useState(${2:'kek'})
```

### ef
```js
useEffect(() => {
  ${1:// ...}
}, [])
```

### rmap
```js
{${1:data}.map((item, ind) => (
  <div key={ind}>Kek</div>
))}
```

### rcmap
```js
{${1:condition} && ${2:data}.map((item, ind) => (
  ${3:<div key={ind}>Kek</div>}
))}
```

### memo
```js
const ${1:SomeComponent} = memo(function ${1:SomeComponent}({ prop }) {
  return (
    ${2:<div>Hello</div>}
  )
})
```

### usememo
```js
const ${1:variableName} = useMemo(() => {
  return ${2:null}
}, [])
```

### usecall
```js
const ${1:functionName} = useCallback(() => {
  ${2: // ...}
}, [])
```

### sel
```js
import { useSelector } from 'react-redux'

const ${1:kek} = useSelector((state) => state${2:kekSlice?.kek})
```

### disp
```js
import { useDispatch } from "react-redux";

const dispatch = useDispatch();
```

<br>


## JS

### log
```js
console.log(${1:'kek'})
```

### if
```js
if (${1:condition}) {
  ${2:// ...}
}
```

### ife
```js
if (${1:condition}) {
  ${2:// ...}
} else {
  ${3:// ...}
}
```

### tr
```js
${1:condition} ? ${2:expresion} : ${3:expresion}
```

### for
```js
for (let i = 0; i < ${1:10}; i++) {
  ${2:// ...}
}
```

### fore
```js
for (let i = 0; i < ${1:10}; i++) {
  ${2:// ...}
} else {
  ${3:// ...}
}
```

### wh
```js
while (${1:condition}) {
  ${1: // ...}
}
```

### sw
```js
switch(${1:expression}) {
  case 'x':
    {2: // ...}
    break;
  case 'y':
    {3: // ...}
    break;
  default:
    {4: // ...}
}
```

### afn
```js
() => {
  ${1:// ...}
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

### stm
```js
setTimeout(() => {
  ${1:// ...}
}, ${2:1000});
```

### sin
```js
setInterval(() => {
  ${1:// ...}
}, ${2:1000});
```

### keys
```js
Object.keys(${1:obj}).forEach((key) {
  ${2:// ...}
})
```

### rndmax
```js
Math.floor(Math.random() * ${1:5})
```
