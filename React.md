**TEMAS REACT JS + REDUX + ES6**


1. Set data structure

    * Es una colección de datos que permite almacenar cualquier tipo de valor.

    * A diferencia de los arrays estos permiten solo valores únicos.

```Javascript
//Inicializar: 
const s = new Set()
```

```Javascript
//Agregar:
s.add('one')
s.add('two')
```

2. Map data structure

    * Es una estructura en la cual se maneja por medio de identificador o llave junto con su valor que puede ser un valor primitivo o bien un objeto.

    * Mantiene el orden en que se insertan.

```Javascript
//Inicializar:
const map1 = new Map();
```

```Javascript
//Agregar:
map1.set('a', 1);
map1.set('b', 2);
```

```Javascript
//Obtener:
map1.get('a');  //Return 1
```

3. Object assign method

    * Es un método que copia los valores de las propiedades enumerables y propias del objeto origen a un objeto destino.

    * Syntax: Object.assign(objetivo, fuentes) 

```Javascript
const object1 = {  a: 11, b: 12, c: 33 };  

const object2 = Object.assign({c: 4, d: 5}, object1);  
console.log(object2.c, object2.d); 

Resultado:
33, 5
```
