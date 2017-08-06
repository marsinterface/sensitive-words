# Example

## Install
```shell
$ npm install senstive-words-11 --save
```

## Import Module
```javascript
const {sensitiveWords} = require('sensitive-words-11')
// Or ES2015 Modules
const {sensitiveWords} from 'sensitive-words-11'
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