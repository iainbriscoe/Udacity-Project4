## Website Performance Optimization portfolio project

launch ngrok for mac
1. doanload ngrok which can be done here: https://ngrok.com
2. the settings for installing ngrok are accessable through the sign up process. 
3. in one terminal window navigate to the folder which contains to index of the file you want to serve.
    -> cd file/path
4. type in python -m SimpleHTTPServer 8080 and hit enter
5. open another teminal window using command N
6. navigate to the location of ngrok on your machine
    -> cd file/path
7. type in ./ngrok http 8080
8. file is now being hosted and is accessible from the link provided on your ngrok account. 




Run the Application

1. navigate to the link title Cam's Pizzaria from index.html. 
2. once on this page scrolling up and down with alter the movement of the pizza background. 
3. When you encounter the slider for pizza size slide it to either end. 
4. youll find that the pizzas on the page adjust size. 






Changes to the Files
index.html

start:
mobile - 28/100 
desktop - 30/100
 
1. compress and resize pizzaria.jpg
2. compress profilepic.jpg

3. Eliminate render-blocking JavaScript and CSS in above-the-fold content
6. Minify HTML,CSS, and javascript files


changes to main.js 
1. added strict to function definitions to create more secure code
2. used the faster document.getElementsByClassName() to replace document.querySelectorAll()
3. reused variable names in several instances to avoid recreating within loops 
4. saved length values outside of loops so that theyre not recaculated on every iteration 
5. took reusable math outside of loops to avoid recalulation 
6. declare var's outside of loops to speed up saving 

Pizza background scrolling 
1. create a significantly smaller amount of pizzas because they are off screen 


pizza resizing 
1. took document.querySelectorAll(".randomPizzaContainer") calculation outside of for loop 
2. didnt evaluate dx new width on every for loop since they were always the same value 






changes to style.css 

1. edited the mover element to include transform: translateZ(0) & backface-visability: hidden 
    to offload the graphic to the GPU 