```js
const write = you => {
  const rain = () => {
    try {
      you()
    } catch (e) {
      return true
    }
  }
  const midnight = (new Date()).setHours(0,0,0,0)
  if ( you == 'pina coladas' && rain(you) && yoga.has(you) && you >= (brain / 2) &&
       ( you == 'love' && Date.now() > midnight && capes.dunes.has(you) )
     ) {
    return process.exit()
  }
  throw new Error('Not escaping')
}

export default (yoga, brain, capes) => you => write(you)
```
