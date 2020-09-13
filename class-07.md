# Domain Modeling :neutral_face:

- **Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain**


## Define a constructor and initialize properties

----------------------------------
var EpicFailVideo = function(epicRating, hasAnimals) {
  this.epicRating = epicRating;
  this.hasAnimals = hasAnimals;
}

var parkourFail = new EpicFailVideo(7, false);
var corgiFail = new EpicFailVideo(4, true);

console.log(parkourFail);
console.log(corgiFail);
---------------------------------
![](https://www.educative.io/api/edpresso/shot/5391633988190208/image/6039922861408256)

- This is object-oriented programming in JavaScript at its most fundamental level.

1. The new keyword instantiates an object.
2. The constructor function initializes properties inside that object using the this variable.
3. The object is stored in a variable for later use.


## Generate random numbers

- the JavaScript standard library includes a Math.random() function for just this sort of occasion.


- example
```
var EpicFailVideo = function(epicRating, hasAnimals) {
  this.epicRating = epicRating;
  this.hasAnimals = hasAnimals;
}

EpicFailVideo.prototype.generateRandom = function(min, max) {
  return Math.floor(Math.random() * (max - min + 1)) + min;
}

var parkourFail = new EpicFailVideo(7, false);
var corgiFail = new EpicFailVideo(4, true);
```

## Tips to follow when building your own domain models.

- When modeling a single entity that'll have many instances:

1. Model its attributes with a constructor function that defines and initializes properties.
2. Model its behaviors with small methods that focus on doing one job well.
3. Create instances using the new keyword followed by a call to a constructor function.
4. Store the newly created object in a variable so you can access its properties and methods from outside.
5. Use the this variable within methods so you can access the object's properties and methods from inside.
-------------------------------------------------------------

# Tables
- The \<table> element is used to add tables to a web page.
- A table is drawn out row by row. Each row is created with the \<tr> element.
- There are several types of information that need to be displayed in a grid or table.
- A table represents information in a grid format.

### Basic Table Structure
1. \<table> : The \<table> element is used to create a table. The contents of the table are written out row by row.
2. \<tr> : You indicate the start of each row using the opening \<tr> tag. It is followed by one or more \<td> elements. At the end of the row you use a closing \</tr> tag.
3. \<td> : Each cell of a table is represented using a <td> element.


## Long Tables
**There are three elements that help distinguish between the main content of the table and the first and last rows**

1. \<thead>:
The headings of the table should sit inside the <thead> element.
2. \<tbody> : The body should sit inside the \<tbody> element.
3. \<tfoot>: The footer belongs inside the \<tfoot> element


## Border & Background

- The border attribute was used on both the \<table> and <td> elements to indicate the width of the border in pixels.
  
 - Example
 ![](https://www.wikihow.com/images/thumb/1/1f/2609629-9-2.jpg/v4-460px-2609629-9-2.jpg.webp)


# Functions, Methods, Objects

- What is function?
- A JavaScript function is a block of code designed to perform a particular task. A JavaScript function is executed when "something" invokes it (calls it).


- What is the object?
1. Objects group together a set of variables and functions to create a model of a something you would recognize from the real world.
2. objects in JavaScript may be defined as an unordered collection of related data, of primitive or reference types.
3. object is an abstract data type with the addition of polymorphism and inheritance. Rather than structure programs as code and data.
4. This object represents a hotel. It has five properties and one method.
5. The object is in curly braces. It is stored in a variable called hotel.

## ADDING AND REMOVING PROPERTIES 
![](https://i2.wp.com/cosmocode.io/wp-content/uploads/2019/04/js-iterating-object-properties.png?fit=712%2C400&ssl=1&w=640)
- Once you have created an object you can add new properties to it. 

- To delete a property, you use the keyword delete, and then use dot notation to identify the property or method you want to remove from the object. 


## GLOBAL OBJECTS NUMBER OBJECT
- Whenever you have a value that is a number, you can use the methods and properties of the Number object on it. 

![](https://i.ytimg.com/vi/YqGtvScabnk/maxresdefault.jpg)

- The Math object has properties and methods for mathematical constants and functions. 


## MATH OBJECT TO CREATE RANDOM NUMBERS
- To get a random whole number between 1 and 10, you need to multiply the randomly generated number by 10. 
- example

```
var randomNum = Math.floor((Math.random() * 10) + l);
var el = document.getElementByid('info');
el .innerHTML = '<h2>random number</h2><p>' + randomNum + 1</p>'; 
```


## More About Functions, Methods,Objects
- An object is a series of variables and functions that represent something from the world around you.
- Functions can take parameters and may return a value. 
- Arrays and objects can be used to create complex data sets.


-----------------------------------------------


[Table Of Content](https://omarxzain.github.io/reading-notes/)
