## Website Performance Optimization portfolio project






To successfully run the pizzas page navigate to the link title Cam's Pizzaria from index.html. once on this page scrolling up and down with alter the movement of the pizza background. When you encounter the slider for pizza size slide it to either end. youll find that the pizzas on the page adjust size. 






Changes to the Files
index.html

start:
mobile - 28/100 
desktop - 30/100
 
1. compress and resize pizzaria.jpg
2. compress profilepic.jpg

3. Eliminate render-blocking JavaScript and CSS in above-the-fold content
6. Minify HTML,CSS, and javascript files


Pizza background crolling 
1. create a significantly smaller amount of pizzas because they are off screen 


pizza resizing 
1. took document.querySelectorAll(".randomPizzaContainer") calculation outside of for loop 
2. didnt evaluate dx new width on every for loop since they were always the same value 
