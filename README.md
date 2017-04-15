##Mobile-Portfolio Project Optimization

Summary of Optimizations:
index.html
28/100 page speed insights
change: profilepic.jpg  pizzeria.jpg
77/100
change: inlined print css
77/100 (no improvement)
change: inlined style css
77/100 (no improvement)
change: inlined javascript perfmatter.js
77/100 (no improvement)
change: made analytics.js request async
78/100
change: made googlefonts load async
78/100
change: prioritized visible content
78/100
change: minified css,html, and javascript (later reversed this change)
78/100
change: used WebFont.load to load fonts asynchronously
97/100

delete some comments
delete unecessary css and js files

pizza.html:
82/100
change:inline css and bootstrap 
97/00

main.js
change: removed multiple document.querySelectorAll(".randomPizzaContainer")
occurrences from inside a loop by creating a new variable
no change in resize timing (~150ms)
change: altered DetermineDx to include pass the offset width into the function instead  of  calculating it
changed resizing to (~2ms)

Scrolling:
21.8ms
change: removed scrollTop query from inside a loop by creating a variable
.5ms

change: reduced number of moving pizzas to 30 from 200 (main.js)

erased inlined css and js files 
