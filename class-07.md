#                      Table 
-	A table represents information in a grid format.
-	Table structure:
-	`Table tag`: to create table, attributes (width=””, cellpading=”5”,cellspacing=”8”,border=”2”,bgcolor=)
-	`th` tag represent the Column name
-	`tr` tag used to create record
-	`td` tag represents the cell in table    also its have `rowspan` attribute to combine 2 cell.
-	`thead` tag contain th tag, `tbody tag `contain main rows ,`tfoot tag` contain last row.


#                     Objects 
- `New` keyword  its used to create blank object .
> Let car=new object();
         Car.name=’BMW’;
         Car.id=123;

- Car.ready:function(){  type code here..  }
- update object : car.name=’toyota’;or  car[‘name’]=’fox’

- delete car.name; to remove property  
- to make property value empty  car.name=’ ‘;
- constructor :its a method used to initialize object .
- Create instance of object   let bmw=new car(‘’,’’)

Two type of object:
1. LITERAL NOTATION   2. OBJECT CONSTRUCTOR NOTATION
- This. Is a pointer  to object

-	array can store a series of object and object hold arrays which it values of properties
