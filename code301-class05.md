## React Docs - thinking in React
1.	How would you break a mock into a component heirarchy? The first thing you’ll want to do is to draw boxes around every component (and subcomponent) in the mock and give them all names

2.	What is the single responsibility principle and how does it apply to components? a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.

3.	What does it mean to build a ‘static’ version of your application?

-         renders your data model 
-      don’t use state at all to build this static version
-       build top-down or bottom-up
4- Once you have a static application, what do you need to add? Identify The Minimal (but complete) Representation Of UI State


5-	What are the three questions you can ask to determine if something is state?

a.   Is it passed in from a parent via props? If so, it probably isn’t state.

  b. Does it remain unchanged over time? If so, it probably isn’t state.
   
c.   Can you compute it based on any other state or props in your component? If so, it isn’t state.

6.	How can you identify where state needs to live?
- Identify every component that renders something based on that state.
-Find a common owner component (a single component above all the components that need the state in the hierarchy).
- Either the common owner or another component higher up in the hierarchy should own the state.
- If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.


 ## Things I want to know more about