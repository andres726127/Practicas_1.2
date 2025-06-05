# Practicas_1.2
Estoy siguiendo un curso de Angular proporcionado por el ing. Santiago Joel Jumbo, en el cual he hecho algúnos proyectos o pequeños códigos para practicar y lograr comprender mejor el curos. A lo largo de el curso pregunte a personas con mejor experiencia en este campo y me recomendaron seguir cursos para aprender las siguientes cosas: HTML, CSS, JS y por ultimo TS 
Los pequeños códigos realizados en el curso de Angular son los siguientes:

App:
```JavaScript
alert('Hola desde app.js');


// console.log("Hola mundo");
let a = 10, 
    b = 20, 
    c = 'Hola ', 
    d = 'Spiderman', 
    x = c + d;

console.log(x);
console.warn(x);
console.error(x);


console.log('%c Mis variables', 'color:black; font-weight: bold');
console.log({a});
console.log({b});
console.log({c});

c = 'Hola de nuevo ';

console.table({a, b, c, d, x});
```

Datos primitivos:
```JavaScript
let nombre = 'Peter Parker';
console.log( nombre );

nombre = 'Ben Parker';
console.log( nombre );

```

Alertas:
```JavaScript
alert('Hola mundo');


let nombre = prompt('Cual es tu nombre?', 'Anonymous');
console.log('*** ' + nombre + ' ***');

const seleccion = confirm('Estás seguro de borrar esto?')
console.log( seleccion );

```


Arreglos:
```JavaScript
// const arr = new Array(10);
// console.log(arr);
// const arr = [];

let videoJuegos = [ 'Mario 3', 'Megaman', 'Chrono Trigger' ];

// console.log({videoJuegos});
// console.log(videoJuegos[0]);

let arregloCosas = [
    true,
    123,
    'Fernando',
    1+2,
    function(){},
    ()=>{},
    ['X', 'Megaman', 'Zero', 'Dr. Light'],
];

// console.log({ arregloCosas });

console.log( arregloCosas[6][3]);


```

Arreglos 2:
```JavaScript
let juegos = ['Mario', 'Minecraft', 'Chrono', 'Lost'];
console.log('Largo:', juegos.length);

let primero = juegos[0];
let ultimo = juegos[ juegos.length - 1 ];

console.log({primero, ultimo});

juegos.forEach( (elemnto, indice, arr) => {
    console.log({elemnto, indice, arr});
} );

let nuevaLongitud = juegos.push('Dragon city');
console.log({nuevaLongitud, juegos});

nuevaLongitud = juegos.unshift('Fire Emblem');
console.log({nuevaLongitud, juegos});

let juegoBorrado = juegos.pop();
console.log({juegoBorrado, juegos});

let pos = 1;
let juegosBorrados = juegos.splice(pos, 2);
console.log({ juegosBorrados, juegos });


```

