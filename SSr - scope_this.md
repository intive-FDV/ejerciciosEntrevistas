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

Explain the difference between outputs.
How can you print 'Carl Tomato' when you execute ```prueba()```?
And 'Jhon Papa'?
