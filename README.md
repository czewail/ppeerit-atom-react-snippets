# ppeerit-atom-react-snippets package

Atom的React开发Snippets插件

#ReactJs

## ppeerit: import empty file [i]
```javascript
import '${1:FilePath}'
```

## ppeerit: import empty [im]
```javascript
import ${1:Name} from '${2:package}'
```

## ppeerit: import empty with object [imo]
```javascript
import {${1:Name}} from '${2:package}'
```

## ppeerit: import react [imr]
```javascript
import React from 'react'
```

## ppeerit: import react-dom [imrd]
```javascript
import ReactDom from 'react-dom'
```

## ppeerit: import prop-types [imp]
```javascript
import PropTypes from 'prop-types'
```

## ppeerit: constructor [cs]
```javascript
constructor(props) {
  super(props)
}
```

## ppeerit: constructor with state [css]
```javascript
constructor(props) {
  super(props)
  this.state = {
    ${1}: ${2}
  }
}
```

## ppeerit: render [rd]
```javascript
render() {
  return (${1:<div>Component</div>})
}
```

## ppeerit: state [st]
```javascript
this.state = {
  ${1}: ${2}
}
```

## ppeerit: setState [sst]
```javascript
this.setState({
  ${1}: ${2}
})
```

## ppeerit: get state [gst]
```javascript
const {${1}} = this.state
```

## ppeerit: get props [gp]
```javascript
const {${1}} = this.props
```

## ppeerit: fn es6 define [fnd]
```javascript
${1:FunctionName} = (${2}) => {
  ${3}
}
```

## ppeerit: componentDidMount [cdm]
```javascript
componentWillUnmount() {
    ${1}
}
```

## ppeerit: Create Component [rc]
```javascript
import React from 'react'

class ${1:MyComponent} extends React.Component {
  render() {
    return (${2:<div>MyComponent</div>})
  }
}

export default ${1}
```

## peerit: Create ReactDom [rc]
```javascript
import React from 'react'
import ReactDom from 'react-dom'

ReactDOM.render(
  ${1:<div>component</div>},
  document.getElementById('${2:app}')
)
```

## ppeerit: Create Component with constructor[rcc]
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

## ppeerit: Create Component with proptypes[rccp]
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

## ppeerit: set prop-types[spt]
```javascript
${1}.propTypes = {}
```

## ppeerit: default prop-types[dpt]
```javascript
${1}.defaultProps = {}
```




....
