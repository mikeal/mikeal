```js
/*   Pratītyasamutpāda   */
/* Dependent Origination */

const a = (_this, that) => {
  if (_this) that()
}
const b = (that) => {
  const _this = false
  // vm knows this will never be called, this code can be dropped
  // and only ever appears in this textual form
  if (_this) that()
}
const c = (_this) => {
  const that = false
  // vm knows this will never be called, this code can be dropped
  // and only ever appears in this textual form
  if (that && _this) return _this
}
```
