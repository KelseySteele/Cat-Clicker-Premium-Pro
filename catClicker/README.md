# Cat-Clicker
In order to use this app, click on the name of the cat that you would like to see and their picture will appear on the right. 

The app is created with JavaScript. The cats' information is stored in an array of objects. Each cat is an object 
with name, number of clicks, and imageURL properties. These properties are stored in the "cat" object constructor.
I used the object constructor because I like having the option to easily add properties without having to add the property name to each object in the array. 

A for loop is used to loop though the cats in the cats array. For each cat, a li element is created. This li element is appended
to a unordered list on the index.html document. 

I used an "iife" (Immediately-Invoked-Function-Espression) to create a click event listener that displays the corresponding cats' properties. This was my first time using an iife.





