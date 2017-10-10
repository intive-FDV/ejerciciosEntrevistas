```javascript
var nombreCompleto = 'Jhon Papa';
var objeto = {
   nombreCompleto: 'Carl Tomato',
   propiedad: {
      nombreCompleto: 'Carlos Lechuga',
      getNombreCompleto: function() {
         return this.nombreCompleto;
      }
   }
};

console.log(objeto.propiedad.getNombreCompleto());

var prueba = objeto.propiedad.getNombreCompleto;

console.log(prueba());
```

make the last console log print the same that the first
