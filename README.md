# ppeerit-atom-react-snippets package

Atom的React开发Snippets插件

#ReactJs

## ppeerit: import empty file [pi]
```javascript
import '${1:FilePath}'
```

## ppeerit: import empty [pim]
```javascript
import ${1:Name} from '${2:package}'
```

## ppeerit: import empty with object [pimo]
```javascript
import {${1:Name}} from '${2:package}'
```

## ppeerit: import react [pimr]
```javascript
import React from 'react'
```

## ppeerit: import react-dom [pimrd]
```javascript
import ReactDom from 'react-dom'
```

## ppeerit: import prop-types [pimp]
```javascript
import PropTypes from 'prop-types'
```

## ppeerit: constructor [pcs]
```javascript
constructor(props) {
  super(props)
}
```

## ppeerit: constructor with state [pcss]
```javascript
constructor(props) {
  super(props)
  this.state = {
    ${1}: ${2}
  }
}
```

## ppeerit: render [prd]
```javascript
render() {
  return (${1:<div>Component</div>})
}
```

## ppeerit: state [pst]
```javascript
this.state = {
  ${1}: ${2}
}
```

## ppeerit: setState [psst]
```javascript
this.setState({
  ${1}: ${2}
})
```

## ppeerit: get state [pgst]
```javascript
const {${1}} = this.state
```

## ppeerit: get props [pgp]
```javascript
const {${1}} = this.props
```

## ppeerit: fn es6 define [pfnd]
```javascript
${1:FunctionName} = (${2}) => {
  ${3}
}
```

## ppeerit: componentDidMount [pcdm]
```javascript
componentWillUnmount() {
    ${1}
}
```

## ppeerit: Create Component [prc]
```javascript
import React from 'react'

class ${1:MyComponent} extends React.Component {
  render() {
    return (${2:<div>MyComponent</div>})
  }
}

export default ${1}
```

## peerit: Create ReactDom [prc]
```javascript
import React from 'react'
import ReactDom from 'react-dom'

ReactDOM.render(
  ${1:<div>component</div>},
  document.getElementById('${2:app}')
)
```

## ppeerit: Create Component with constructor[prcc]
```javascript
import React from 'react'

class ${1:MyComponent} extends React.Component {
  constructor(props) {
    super(props)
  }

  render() {
    return (${2:<div>MyComponent</div>})
  }
}

export default ${1}
```

## ppeerit: Create Component with proptypes[prccp]
```javascript
import React from 'react'
import PropTypes from 'prop-types'

class ${1:MyComponent} extends React.Component {
  render() {
    return (${2:<div>MyComponent</div>})
  }
}

${1}.propTypes = {}

${1}.defaultProps = {}

export default ${1}
```

## ppeerit: set prop-types[pspt]
```javascript
${1}.propTypes = {}
```

## ppeerit: default prop-types[pdpt]
```javascript
${1}.defaultProps = {}
```




....
