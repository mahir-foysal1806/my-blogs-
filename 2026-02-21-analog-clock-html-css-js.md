#building an analog clock using HTML ,CSS and jsvaScrept
TOday , i built a full functional analog clock using **HTML,css,javascrept**.
this project help me strengthen my front-end skills and understand how javascript interacts with the DOM.

##approach 
1.**Html Structure**
-created a `div` for clock container.
-Added `div` s for the hour .minute,second.
2.**CSS styling**
-Designed the clock face with circles and ticks 
-Sryled each hand with diffferent lengths and color .
-Used ~transfrom-origin~ to roted hand from the center .
3.**Javascrept**
-Used `date` to get current timme .
-Calculated degrees for hour,minute,and second hands:```javascrept 
    let hours=now.getHours()%12;
    let minutes=now.getMinutes();
    let seconds=now.getseconds();
    let hourDeg=(hours+minute/60)*30;
    let minuteDeg=(minute+second/60)*60;
    let secondDog=second*6;
-updated hand rotation every second with `setIntervel`

##lessons learned 
-learned how to use **css transfrom**for rotation.
-practiced **DOM manipulation with js**
-learned how **time calculation works for analog clocks**
-combining HTML,CSS,AND JS brings interactive project to life .
##Next steps
-Add **dynamic themes**(dark/light mode)
-MAke it **responsive**for different screen sizes.
-Add **digital time display** inside the clock
This mini project taught me that front-end is all about **visual intteraction +logic**.
small project like this improve both coding skills and design sense.
