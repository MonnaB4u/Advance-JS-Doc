# Advance-JS-Doc-For-React

## Java-Script ES6

### 1 Tamplate String

```
Tamplate String declare by backticks ( ` ` ) ---- for example there have an array :-

const numbers = [10, 20, 30, 40, 50, 60, 70, 80, 90 ]

const Student = {
    name: 'Monna',
    age: 23,
    dresses: ['shirt', 'pant', 'shoes']
}

console.log(` My name is ${Student.name} , Age ${Student.age} ,My dressCode is ${Student.dresses} `)

console.log(`My ID number is ${numbers[3]},My name is ${Student.name} , Age ${Student.age} ,My dressCode is ${Student.dresses}`)

```
##  Arrow function

###Arrow function is called sortcut function; for example :-

```
 *** normal function is look like

 ****  function Student(){

        return 0
          
          }

 *** Arrow function look like this :-

*** ex:1 :- const Student = id => console.log(id)
             Student(30)

*** ex:2 :- const Student = (id,name) => console.log(id, name); 
             Student(Monna ,30)
             
*** ex:3 :- const add = (x, y) => x + y;

```
## Spread operator
### (...) three dots . is called Spread operator . Spread operator allow quickly copy object or value in the another array or onject ;
```
*** Example ....... we have an array .

const age = [10, 20, 30, 40, 50, 60, 70, 80, 90 ]
const allAge=Math.max(...age)
console.log(allAge)

```

## Map 

### In javascript map used to find selected items from array or object

```
const persons = [
  {firstname : "Malcom", lastname: "Reynolds"},
  {firstname : "Kaylee", lastname: "Frye"},
  {firstname : "Jayne", lastname: "Cobb"}
];

const name=persons.map(data=> console.log(data.firstname + " " + data.lastname) )
```

## Filter 

```
const age = [10, 20, 30, 40, 50, 60, 70, 80, 90 ]
const bigger= age.filter(data=> data > 30)
console.log(bigger)
```

## Find

```
const age = [10, 20, 30, 40, 50, 60, 70, 80, 90 ]
const bigger= age.filter(data=> data > 30)
console.log(bigger)
ans only 40
```
## Slice
```
const age = [10, 20, 30, 40, 50, 60, 70, 80, 90 ]
const sliceNumber= age.slice(3, 8)
console.log(sliceNumber)
```

## Splice
### Splice use delete and add data

```
const age = [10, 20, 30, 40, 50, 60, 70, 80, 90 ]
const spliceNumber= age.splice(3, 8)
console.log(spliceNumber)

```









