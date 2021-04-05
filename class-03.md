Chapter 3 : list
Theres 3 type of list:
1.orderd list: the list item will be number not point.
    . we used ol tag to declarer ordered list and li tag for list item
2. unordered list: the list item will be with bullet point.
      . we used ul tag to declarer unordered list and li tag for list item

3- definition lists: are made up of a set of terms along with the definitions for each of those terms.
.     we used dl tag to declarer Definition list and dt tag for the being term of definition and dd tag used to the definition. 

-	We can used nested list in list item can put anther list type

Chapter 13: Box
- box is sized just big enough to hold its contents. and the dimensions for the box represent by heights and width.pixle is the popular way  to width and heights.

-min and max width:
     . min width: the smallest size a box can be displayed at when the browser window is small window  
     .Max width :the maximum width a box can stretch to when the browser window is wide.
-min and max height: the thing for width but this for height
-overflow we used it if the content size big than box
-each box have three properties :
1. Border 2.margin 3 padding
- The border-width property is used to control the width of a border:can work with pixel or with values( thin ,medium, thick).
-border-style property:( solid, dotted, dashed, double)
- border-color property
- border property :allows you to specify the width, style and color of a border in one property
-padding property: allows you to specify how much space should appear between the content of an element and its border.

- margin property: controls the space between  elements .
-To center   box in browser we will set left-margin and right-margin to auto.
- display property: allows you to turn an inline element into a block-level element or vice versa, and can also be used to hide an element from the page.( inline, block, inline-block, none);
- visibility(hidden, visible);

                                      JavaScript
ARRAYS: are special types of variables that store more than one piece of related information.
-we used it when we not know how many elements should allocate storage for it;
-Two way to create array:
    1.let username=[‘osama’,’ahmad’,1];
    2. let username =new array(‘osam’,ahmad’);
-each value in array have index starting from 0;
-.length ; return number of element.

-A switch statement: starts with a variable called the switch value. 
Each case indicates a possible value for this variable and the code that should run if the variable matches that value.

Switch(){

Case ‘one’:

Count++;

Break;

Default :

Count--;

Break;
}
-	JavaScript is weak type , because that we should used strict equals .

-LOOP
To execute a set of code in one block until condition not met and to reduced redundant code 3 type of loop
1.	For: used when the iteration (time ) know. like print ur Name 10 time.
For (initialization, condition ,update)
{ set of code, }

2 . while :used if we not know the # of iteration .
While(condtion) { Execute code }

3.do..While:is the same while the key different is the code will execute at least one time .
Do{ Execute code at least 1 before checking condition }while();