# random-food

This is my first npm proyect, the code is just for random food in Argentina.

## install

```npm
npm i random-food
```

# Usage

```bash
random-food

🧉Example of use
/*
const ran = require('random-food');

let ran2 = ram.randomFood()

console.log(ram2)
*/


🎲THE CODE INSIDE OF RANDOM

const comidasArgentinas = [
    "Ñoquis",
    "Empanadas",
    "Lasaña",
    "Hamburguesa",
    "buñuelos",
    "Guiso",
    "Asado",
    "Fideos a la boloniesa ñ",
    "Locro"
]

const randomFood = () => {
    const comida = comidasArgentinas[Math.floor(Math.random() * comidasArgentinas.length)];
    console.log(comida);
}

/*A better code to add in the future, No undefined

const comidasArgentinas = [
    "Ñoquis",
    "Empanadas",
    "Lasaña",
    "Hamburguesa",
    "buñuelos",
    "Guiso",
    "Asado",
    "Fideos a la boloniesa ñ",
    "Locro"
]

const randomFood = () => {
    const comida = comidasArgentinas[Math.floor(Math.random() * comidasArgentinas.length)];
    return comida;
}

randomFood()

*/

//without the exports module 😋
```

# Contributing
If someone wants to add or improve something, I invite you to collaborate directly in this repository: [npm-random-food] (https://github.com/Plexor-dev/npm-random-food)

# License
random-msg is released under the [MIT License](https://opensource.org/licenses/MIT).
