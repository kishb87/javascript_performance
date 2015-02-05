## Website Performance Optimization portfolio project

Running Applicaton
1. Open index.html in browser
2. To view pizza.html, click Cam's Pizzeria in index.html

Optimizations Made

Index.html
1. Created style tag in index.html to load critical CSS faster
2. Asynced JS files to prevent render blocking
3. Created print media query for print.css to prevent render blocking
4. Minified CSS
5. Created pizzeria-small.png at smaller resolution from original pizzeria.png

Main.js
1. Removed document selection js variables from changePizzaSizes and updatePositions functions in main.js
2. Reduced number of pizzas rendered when scrolling page (ln 532 --> 200 pizzas to 20 pizzas)
3. Created a smaller pizza.png file called pizza-small.png
4. Minified JS
