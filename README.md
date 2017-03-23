# Atom React ES.next Snippets
React ES.next snippets for Atom

## General snippets

### `resc` - React component
```javascript
import React, { Component, PropTypes } from 'react';

export class ${1} extends Component {
  render() {
    return (${2:<div>MyComponent</div>});
  }
}

${1}.propTypes = {
};

export default ${1};
```

### `resfunc` - React functional component
```javascript
import React, { PropTypes } from 'react';

const ${1} = () => {
  return (
    ${2:<div>MyComponent</div>}
  );
};

${1}.propTypes = {
};

export default ${1};
```

### `resfuncm` - React functional component (Minimal)
```javascript
import React from 'react';

const ${1} = () => (
  ${2:<div>MyComponent</div>}
);

export default ${1};
```

### `resstate` - React initial state definition
```javascript
  state = { ${1}: ${2} };
```

### `resmethod` - React method definition
```javascript
${1} = () => {

}
```

### `respt` - React prop types definition
```javascript
${1}.propTypes = {
  ${2}
};
```

### `resdp` - React default props definition
```javascript
${1}.defaultProps = {
  ${2}
};
```

## PropType snippets

### `respstring` or `respstringr` - String
```javascript
${1}: PropTypes.string,
```

### `respnumber` or `respnumberr` - Number
```javascript
${1}: PropTypes.number,
```

### `respobject` or `respobjectr` - Object
```javascript
${1}: PropTypes.object,
```

### `resparray` or `resparrayr` - Array
```javascript
${1}: PropTypes.array,
```

### `respbool` or `respboolr` - Boolean
```javascript
${1}: PropTypes.bool,
```

### `respel` or `respelr` - Element
```javascript
${1}: PropTypes.element,
```

### `respfunc` or `respfuncr` - Function
```javascript
${1}: PropTypes.func,
```

### `respnode` or `respnoder` - Node
```javascript
${1}: PropTypes.node,
```
