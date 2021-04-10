## DOM

-Object consist of propriety like (name.id ) and method which it the behaver of the object .
-Objects consist of a set of name/value pairs.
> Literal notation is easiest and most popular way to create objects:
 
   Let human ={ 

Name:’osama’,

Id=12343443,

Gender =’m’,

checkAvailability():function()
 {
Return this name – this. Id}
  }
- to access to properties and method we used dot . like  osama. checkAvailability();

## Dom (Document Object Model )  
-	specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser
Dom responsible for : 
1.	MAKING A MODEL OF THE HTM L PAGE
2.	ACCESSING AND CHANGING THE HTML PAGE

-	Each node is an object with methods and properties.
-	Scripts access and update this DOM tree and then the browser will reflect that change.
-	ATTRIBUTE NODES : HTML elements can carry attributes and these are represented by attribute nodes in the DOM tree.
-	TEXT NODES: Once you have accessed an element node, you can then reach the text within that element.
### To access and update DOM  tree involves two steps:
 1: Locate the node that represents the element you want to work with. 
-	SELECT AN INDIVIDUAL ELEMENT NODE 

 > & get El ementByld () , querySelector(),

-	SELECT MULTIPLE ELEMENTS (NODELISTS)
> & getElementsByClassName(),getElementsByTagName(),querySelectorAll()
-	TRAVERSING BETWEEN ELEMENT
> & parentNode, previousSibling/nextSibling, firstChild / lastChild

2: Use its text content, child elements, and attributes.
-	ACCESS/ UPDATE TEXT NODES
     > nodeValue: This property lets you access or update contents of a text node.
- WORK WITH HTML CONTENT:
      > innerHTML, textContent

      > create Element()

      > createTextNode()

      >appendChild() / removeChild()

- ACCESS OR UPDATE ATTRIBUTE VALUES:
    > hasAttribute()

    > getAttribute() 

    > setAttribute()

   > removeAttribute()


- DOM queries may return one element, may return a Nodelist, which is a collection of nodes.
- Nodelist(collection):its consist of more than one node.
- getElementByid () and querySelector( ‘css selector`) : return one elements .

- Nodelist(collection): have 2 method `1.length ``2. Item()`
