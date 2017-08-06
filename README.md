# Example

## Install
```shell
$ npm install senstive-words --save
```

## Import Module
```javascript
const {sensitiveWords} = require('sensitive-words')
// Or ES2015 Modules
const {sensitiveWords} from 'sensitive-words'
```

## Usage
```javascript
const filtered = sensitiveWords(
    'The new apple macbook pro will have a touchbar',
    ['pro', 'touchbar']
)

console.log(filtered)

// The new apple macbook *** will have a ***
```