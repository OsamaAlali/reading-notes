## React Docs - lists and keys:

1.	What does .map() return? Return new array
2.	If I want to loop through an array and display each value in JSX, how do I do that in React? In the first: I have array has collection of data  will move over them by map method each time  will return li tag { item }  close tag and  all list will save in new array this array will called by parent inside ul tag also we can or used them interal. 
3.	Each list item needs a unique __key __.
4.	What is the purpose of a key? Each list will have attribute with unique value to let react identify which item change, add, remove, double Click (make background red)
-index can be used as value for id attribute . but this not good solution

##  The Spread Operator: 

1.	What is the spread operator? Three DOT (…) allows an Iterable 
2.	List 4 things that the spread operator can do.

                a. adding items to arrays
                b. combining arrays or objects
                c. spreading an array out into a function’s arguments.

3.	Give an example of using the spread operator to combine two arrays.

>firstA=[‘osama’,’alali’];
firstB=[‘+962777216147’];
description =[…firstA , …firstB];
console.log (…description);  // osama alali +962777216147’

4.	Give an example of using the spread operator to add a new item to an array.
 >> firstA=[‘osama’,’alali’];

 >>firstB=[‘+962777216147’,…firstA];

>>console.log (…firstB);  //// +962777216147 osama alali

5.	Give an example of using the spread operator to combine two objects into one.
>>firstA= { fName: ‘osama’}

>>firstB={sName:’Alali’}

>>fullName =[…firstA , …firstB];
console.log(…fullName);  // osama alali 




## How to Pass Functions Between Components

1.	In the video, what is the first step that the developer does to pass functions between components? Create function then  pass it to childe
2.	In your own words, what does the increment function do?its take name as parmeter  then it search wheres  name is identical to increase  count by one 
3.	How can you pass a method from a parent component into a child component? He pass method with person tag  
4.	How does the child component invoke a method that was passed to it from a parent component? this .props.increment(this.props.name) in child method 
