<div align="center">

  

  <h1>FLP PROJECT</h1>
  
  <p>
    <b>PROYECTO DE FUNDAMENTOS DE LENGUAJES DE LA PROGRAMACIÓN</b>
  </p>

  

   
<h4>
  <span> · </span>
    <a href="https://docs.racket-lang.org/eopl/index.html">Documentation</a>
  </h4>
</div>

<br />

  

<!-- About the Project -->
## :star2: About the Project

***This project covers all the concepts seen in the Fundamentals of Programming Languages course, in which a language is developed using Dr. Racket's SLLGEN library and based on the teacher's guide -> [Youtube](https://www.youtube.com/watch?v=kI9sWhWVIMI&list=PLi3X2PHYk7zTmdZNBiAe0c5S_-gAjBGeC)***

 [![intro.png](https://i.postimg.cc/qvXhkCM9/intro.png)](https://postimg.cc/tsJCkJ65)



<!-- TechStack -->
### :space_invader: Tech Stack


<details>
<summary>Doc and information about proyect</summary>
  <ul>
    <li><a href="https://docs.racket-lang.org/eopl/index.html/">DOC RACKET</a></li>
    <li><a href="https://www.youtube.com/watch?v=kI9sWhWVIMI&list=PLi3X2PHYk7zTmdZNBiAe0c5S_-gAjBGeC">Course</a></li>
  </ul>
</details>



<!-- Usage -->
## :eyes: INSTRUCTIONS FOR USE

## Arithmetic
```
To perform additions, simply type in the interpreter
(1+2+2+3+4+5+6+7+8+9)
(1+-2+2+3+-4+21+21+44+533+123)
(5312+-2321+3213+213+-32+232+321+212+21)
[2 + 2]
[3 + 5]
[9 * 5]
[10 - 2]
[31 % 21]
[21 add1 0]
[21 sub1 0]
[300 / 2]
["Hola" concat "Mundo"]
```


## Conditional block
```
To perform conditionals, it is declared as follows example:

if .[{2 < 3} and {10 == 5}] then "Verdadero" else "Falso"
if .[{2 >= 3} or {9 != 5}] then true else false
if .[{2 != 3} and {7 < 5}] then true else false
```


## Arrays
```
Added a visual way of arrays with limited functionality, but essential for basic operations.

Array.[1,2,3,4,5,6,7,8,9,10,321,21,3,4,21].length
Array.[1,2,3,4,5].length
Array.["Hola","Mundo"].concat
Array.[1].add1
Array.[1,4].+
Array.[1,2].*
Array.[1,3,5,6].-
Array.[20,6].%
```


## Boolean
```
Boolean Primitives

true --> #t
false ---> #f
{2 < 3}
{20 > 4}
{100 >= 100}
{500 <= 4231}
{100 != 213}
{9900 == 300}
```


## Logical Operators
```
Basic Logical Operators

Example:
.[{2 < 3} and {3 > 1}]
.[{2 < 3} or {3 > 1}]
.[{2 < 3} not {2 > 5}]
```

## Environments
```
Example:
let x = 200 in x
let q = proc(x,y) [Array.[x].sub1 + [500 % 3]]in ((q 9 z))
let z  = [x + 2] in z
```

## Set!
```
Example:
set x := 20
set z := 100
set a := "Hola"
set b := "Mundo"
```

## Proc
```
Example:
let a = proc(x,y) x in a
let b = proc(x,y,z) [x,y].+ in b
let x = proc(a,b,c,d) x in a
```

## Console Log
```
Example:
console.log("Hola Mundo")
console.log("Hello World")
```


## App-exp
```
Example:
let x = 5 in let f = proc(y,z) [y + [z - x]] x = 28
in ((f 2 x))
let z = 534 in let k = proc(y,z) [b + [x - a]] x = 2218
in ((k 2 x))
```

## Begin
```
Example:
let x = 100 in let p = proc(x) begin set x := [x add1 0] x end in [((p x)) + ((p x))]
let x = 2 in begin set x := 9 x end
```

## Project statement

[ProyectoFinal.pdf](https://github.com/Kahyberth/FLP-PROYECT/files/10181414/ProyectoFinal.pdf)



<!-- Contributing -->
## :wave: Contributing

<a href="https://github.com/Kahyberthg/FLP-PROYECT/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Kahyberthg/FLP-PROYECT" />
</a>



<!-- License -->
## :warning: License

Distributed under the no License.


<!-- Contact -->
## :handshake: Contact

Kahyberth - [@SG5882](https://twitter.com/SG5882) - kahyberthst@gmail.com






