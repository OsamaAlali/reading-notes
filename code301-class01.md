>#  Component-Based Architecture:
   -DESIGN PAGE BU SPLIT IT TO COMPONETS WhICH  contains method ,event , propertis,
In order to component  reusability 
- It provides a higher level of abstraction and divides the problem into sub-problems, each associated with component partitions

># What is a Component?

A component is a software object, intended to interact with other components
###Views of a Component :
1.	Object-oriented view :Using Class  which have attribute and method .
2.	Conventional view :using function
3.	Process-related view: you will not build everything from scratch  there’s (user interface) UI using it to Drag and dorp  components.

>###  Characteristics of Components
1. Reusability   2. Replaceable   3. Not context specific 4. Extensible 5. Encapsulated
    6. Independent

>### What are the advantages of using component based architecture?

-	` Ease of deployment `   `  Reduced cost `   ` Ease of development `  ` Reusable `` Independent `
 ` Modification of technical complexity `    ` Reliability `   ` System maintenance and evolution `





?## What is Props? 
 
Is a way  to make component communicate together  through passing data   between them  this Data called props( data passing one way `top –down` and its const value)
  
>## How are props used in React?

 -`first step `by create attribute with Value  and then assign attribute with Components or directly created in components 
   >>Let name =”osama”;
   >> App(){
  >>Return  (
  >><Copm1 firstName={name}  lastName={“AlAli”} 
  )}
  

-`second step ` we will using Props Object to access to props data in child components’  as parameters  and will using props with` . notation ` to get value  from parent and render it .
>const ChildComponent = (props) => {  
  return <p>{props.name +’ ’+ props.lastName}</p>; 
};
## What is the flow of props?  
The props is  flow top –down   from parent to child  in one-way u cant pass data from child to parent  and u cant change that value of props attribute directly  u just need to used setState    method to update value

## Things I want to know more about 

