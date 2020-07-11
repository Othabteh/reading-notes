## JavaScript Chapter 3 *(Object Literals)*

Objects group together a set of variables and functions to create a model of something you would recognize from the real world. In an object, variables become properties and functions become methods. 
- Properties tell us about the object, such name, age, gender, etc. 
- Methods represent tasks that are associated with the object. For example you can check how many rooms are available in a hotel. 


 
#### Literal Notation:
```
 var hotel = {
    <dd>name: 'Hilton", <br>
    rooms: 40, <br>
    booked: 25, <br>
    checkAvailability: function() { <br>
      return this.rooms - this.booked; <br>
    } 
  <dt>}
```

#### DOT Notation
You access the properties or methods of an oject using the dot notation. 
> var hotelName = hotel.name;

> var roomsFree = hotel.checkAvailability();



## JavaScript Chapter 5 *(Document Object Model)*

The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.

Methods that select individual elements:
- getElementById( ) - document.getElementById('one')
- querySelector( )

Selecting an element fron a nodelist:
- item( ) 
- array syntax

Adding or Removing HTML content:
- innerHtML
- DOM Manipulation
