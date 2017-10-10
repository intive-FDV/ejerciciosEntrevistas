```javascript
function esGrande (coso) {
  if (coso == 0 || coso == 1 || coso == 2) {
    return false
  }
  return true
}
console.log(esGrande(1))    // false
console.log(esGrande([2]))  // false
console.log(esGrande([3]))  // true
```

Explain the difference

```javascript
function esGrande (coso) {
  if (coso == 0 || coso === 1 || coso === 2) {
    return false
  }
  return true
}
console.log(esGrande(1))    // false
console.log(esGrande([2]))  // true
console.log(esGrande([3]))  // true
```
