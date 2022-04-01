<p align="center">
<img src="https://img.shields.io/badge/LINUX-darkgreen.svg"/>
<img src="https://img.shields.io/badge/Shell-ligthgreen.svg"/>
<img src="https://img.shields.io/badge/Emacs-purple.svg"/>
<img src="https://img.shields.io/badge/JavaScript-yellow.svg"/>
<img src="https://img.shields.io/badge/Markdown-black.svg"/><br>	
</p>

---

# JavaScript

While `HTML` and `CSS` control the content and styling of a page, JavaScript is used to make it interactive. In the `JavaScript Algorithm and Data Structures Certification`, you'll learn the fundamentals of `JavaScript` including `variables`, `arrays`, `objects`, `loops`, and `functions`.

Once you have the fundamentals down, you'll apply that knowledge by creating algorithms to manipulate `strings`, `factorialize numbers`, and even calculate the orbit of the International Space Station.

Along the way, you'll also learn two important programming styles or paradigms: *Object Oriented Programming (OOP)* and *Functional Programming (FP)*.

### Basic JavaScript

`JavaScript` is a `scripting language` you can use to make web pages interactive. It is one of the core technologies of the web, along with `HTML` and `CSS`, and is supported by all modern **`browsers`**.

This repo contains the tasks for learn and practice the fundamental programming concepts in `JavaScript`. Starting with basic `data structures` like `numbers` and `strings`. Then learn to work with `arrays`, `objects`, `functions`, `loops`, `if/else statements`, and more.

1.  [JavaScript Algorithms and Data Structures](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures)
2.  [Basic JavaScript](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#basic-javascript)

## Accessing Nested Arrays

As we have seen in earlier examples, objects can contain both nested objects and nested arrays. 
Similar to accessing nested objects, array bracket notation can be chained to access nested arrays.

### Here is an example of how to access a nested array:

```bash

    const ourPets = [
      {
        animalType: "cat",
        names: [
          "Meowzer",
          "Fluffy",
          "Kit-Cat"
        ]
      },
      {
        animalType: "dog",
        names: [
          "Spot",
          "Bowser",
          "Frankie"
        ]
      }
    ];
    
    ourPets[0].names[1];
    ourPets[1].names[0];
```

`ourPets[0].names[1]` would be the string `Fluffy`, and `ourPets[1].names[0]` would be the string `Spot`.

---

## Task

+ [x] **Using dot and bracket notation, set the variable `secondTree` to the second item in the `trees` list from the `myPlants` object.**
	* `secondTree` should equal the string `pine`.
	* Your code should use dot and bracket notation to access `myPlants`.

	+ **[Get a Hint](https://forum.freecodecamp.org/t/16160)**

```bash
const myPlants = [

  {
    type: "flowers",
    list: [
      "rose",
      "tulip",
      "dandelion"
    ]
  },
  {
    type: "trees",
    list: [
      "fir",
      "pine",
      "birch"
    ]
  }
];

const secondTree = "";
```
---

## Credits

## Author(s):blue_book:

Work is owned and maintained by **`Alex Orland Arévalo Tribaldos`**.

<aoarevalot@gmail.com>
	
[![M](https://upload.wikimedia.org/wikipedia/commons/thumb/9/91/Octicons-mark-github.svg/25px-Octicons-mark-github.svg.png)](https://github.com/Alexoat76)
[![M](https://upload.wikimedia.org/wikipedia/fr/thumb/c/c8/Twitter_Bird.svg/25px-Twitter_Bird.svg.png)](https://twitter.com/aoarevalot)
[![M](https://upload.wikimedia.org/wikipedia/commons/thumb/c/ca/LinkedIn_logo_initials.png/25px-LinkedIn_logo_initials.png)](https://www.linkedin.com/in/Alexoat76/)

## Acknowledgments :mega: 

### **`freecodecamp`**
	
**FreeCodeCamp** is a non-profit organization that consists of an interactive learning web platform, 
an online community forum, chat rooms, online publications and local organizations that 
intend to make learning web development accessible to anyone.

+ For more information, please visit [this link](https://www.freecodecamp.org/).

![Brand](https://upload.wikimedia.org/wikipedia/commons/f/fa/FreeCodeCamp_logo.svg)
