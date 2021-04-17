Flash is a very popular technology used to add animations, video, and audio to websites.
- We can used: Width and height to control on image size.
- using float: left or right to move image.
- By default, images are inline elements. This means that they flow within the surrounding text.
- To centralize image : change image to inline block element and set the values of the left and right margins to auto.
background-image: body {background-image: url("images/pattern.gif");}
-Repeating Image:
     - background-repeat: 
        1. repeat: The background image is repeated both horizontally and vertically
       2. repeat-x : The image is repeated horizontally only
        3. repeat-y : The image is repeated vertically only.
        4. no-repeat : The image is only shown once.
      - background-attachment: 
      1. fixed: The background image stays in the same position on the page
      2. scroll: The background image moves up and down as the user scrolls up and down the page.
- background-position: Can used it when image not repeat, To specify where in the browser window the background image should be placed. (left top, left center, right top, right center). the default value will be center
