# react-mtg-svg
Mtg Icon in svg for react

## Installation
This library was built with React >=18
in mind. It *might* work on lower versions
as well, but the lib is developed for and tested on those versions.
```
npm install @remyar/react-mtg-svg --save
```

## Usage
The lib exposes the following component:

class is optionnal
height is optionnal
width is optionnal

### MtgSvg
``` javascript
import MtgSvg from '../mtgSvg'
...

function YourReactComponent(props) {
    return <div>
        <MtgSvg
            svgName={"svg_" + block.code}
            class={"rarity_" + card.rarity}
            height="24px"
            width="24px"
        />
        </div>
}

export default YourReactComponent;
``` 