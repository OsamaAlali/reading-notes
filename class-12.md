-	Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool.
-	canvas element: draw the graph onto the page
-	to draw line we used: var buyers = document.getElementById('buyers').getContext('2d');
 new Chart(buyers).Line(buyerData);
-	Drawing a pie chart:
-	var countries= document.getElementById("countries").getContext("2d");
-	new Chart(countries).Pie(pieData, pieOptions);
-	fillRect(x, y, width, height) Draws a filled rectangle.
-	strokeRect(x, y, width, height) Draws a rectangular outline.
-	clearRect(x, y, width, height) Clears the specified rectangular area, making it fully transparent.

