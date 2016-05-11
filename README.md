## Website Performance Optimization portfolio project ##

TASK 1:
What: To acheive a score of 90/100 on the Google speed load tests pn both mobile and desktop. 
How: Using a combination of minify code, image compression and async'ing to JS links and inline CSS.

My scores were 96 on mobile and 94 on desktop.

TASK 2: 
What: To acheive 60 FPS on the Pizza rendering and to to resize pizzas so its less than 5 ms using the pizza size slider. 
How: Using chrome dev tools I was able to pinpoint were the issues were in the CRP and make the amendmants in the main.js file accordingly. This included creating variables and taking them outside the loop, so when the page was rendered it didnt loop through everytime.

SETUP:
To run the project, simply:
1. Deploy locally (using pythons SimpleHTTPServer or any other tool)
2. install ngrok and tunnel your http server port
3. get the link from ngrok and paste it into PageSpeedInsights
4. open pizza.html in the broswer, check out chrome's dev tools and measure the speed


