```javascript
let perro = {
  nombre: 'lolo',
  decirNombre () {
    console.log(this.nombre)
  }
}
let decirNombre = perro.decirNombre
decirNombre()
```
This print prints something different from "lolo". Why?
How can you fix it?
